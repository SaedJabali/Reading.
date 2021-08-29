# Location

The app can request the last known location of the user's device, using the Google Play services location APIs.

### Set up Google Play services

To access the fused location provider, your app's development project must include Google Play services. Download and install the Google Play services component via the SDK Manager and add the library to your project. For details, see the guide to Setting Up Google Play Services.

### Specify app permissions

Apps whose features use location services must request location permissions, depending on the use cases of those features.

### Create location services client

In activity's onCreate() method, create an instance of the Fused Location Provider Client as the following code snippet shows.

```java
private FusedLocationProviderClient fusedLocationClient;
@Override
protected void onCreate(Bundle savedInstanceState) {
    fusedLocationClient = LocationServices.getFusedLocationProviderClient(this);
}
```

### Get the last known location

Once you have created the Location Services client you can get the last known location of a user's device. When your app is connected to these you can use the fused location provider's getLastLocation() method to retrieve the device location. The precision of the location returned by this call is determined by the permission setting you put in your app manifest, as described in the guide on how to request location permissions.

To request the last known location, call the getLastLocation() method. The following code snippet illustrates the request and a simple handling of the response:

```java
fusedLocationClient.getLastLocation()
.addOnSuccessListener(this, new OnSuccessListener<Location>() {
@Override
public void onSuccess(Location location) {
// Got last known location. In some rare situations this can be null.
if (location != null) {
// Logic to handle location object
       }
   }
});
```



