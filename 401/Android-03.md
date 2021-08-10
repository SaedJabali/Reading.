# RecyclerView

## What is RecyclerView

RecyclerView is a list drawing library that provides a fixed size window to load a large data.
It recycles the views it created at the begining when the views go out of window and then if there is a **need**, reuses them for new items.

## Key classes

Several different classes work together to build a dynamic list.

* RecyclerView is the *ViewGroup* that contains the views corresponding to the data.

* Each individual element in the list is defined by a view holder object. When the view holder is created, it doesn't have any data associated with it. After the view holder is created, the RecyclerView **binds** it to its data.

* The RecyclerView requests those views, and binds the views to their data, by calling methods in the adapter.

* The layout manager arranges the individual elements in the list.

## Implementing your RecyclerView

* First of all, decide the shape/layout of the list or grid.

* Design the beahvior of the elements in the list.

* Define the Adapter that associates your data with the ViewHolder views.

## Layout

RecyclerView arranges the elements using layout.manager class, this class has three layouts

1. **LinearLayoutManager** arranges the items in a one-dimensional list.

2. **GridLayoutManager** arranges all items in a two-dimensional grid:
If the grid is arranged vertically, GridLayoutManager tries to make all the elements in each row have the same width and height, but different rows can have different heights.
If the grid is arranged horizontally, GridLayoutManager tries to make all the elements in each column have the same width and height, but different columns can have different widths.

3. **StaggeredGridLayoutManager** is similar to GridLayoutManager, but it does not require that items in a row have the same height (for vertical grids) or items in the same column have the same width (for horizontal grids). The result is that the items in a row or column can end up offset from each other.

## Implementing your adapter and view holder

When defineing the adapter, you need to override three key methods:

onCreateViewHolder(): RecyclerView calls this method whenever it needs to create a new ViewHolder.

onBindViewHolder(): RecyclerView calls this method to associate a ViewHolder with data.

getItemCount(): RecyclerView calls this method to get the size of the data set.
