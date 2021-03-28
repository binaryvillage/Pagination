# Pagination
In a programming language of your choice, create a PaginationHelper class that might be used for
implementation of pagination UI components and a set of Unit tests to properly test it.

Here is a class description:
/*
The class is designed to take in an array of values and an integer indicating how many items will be
allowed per each page. The types of values contained within the collection/array are not relevant.
The following are some examples of how this class is used:

helper = PaginationHelper.new(['a','b','c','d','e','f'], 4)
helper.pageCount() # should == 2
helper.itemCount() # should == 6
helper.pageItemCount(0) # should == 4
helper.pageItemCount(1) # last page - should == 2
helper.pageItemCount(2) # should == -1 since the page is invalid

//page_index takes an item index and returns the page that it belongs on

helper.pageIndex(5) # should == 1 (zero based index)
helper.pageIndex(2) # should == 0
helper.pageIndex(20) # should == -1
helper.pageIndex(-10) # should == -1 because negative indexes are invalid
*/
