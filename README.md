# react-pagination
ReactJs Pagination

#How to use it
```<Pagination
    totalRecords={this.state.totalRecords} // Total Number of Records (e.g. 1000)
    pageSizes={this.state.pageSizes} // Page Sizes Options (e.g. [10, 20, 50, 100, 200])
    pageSizeSelected={this.state.pageSizeSelected} // Selected Page Size Options (e.g. 50)
    currentPage={this.state.currentPage} // Current Page (e.g. 1)
    onPageChange={this.handlePageChange} // Callback on current page and page size change, can be used to make api call
/>```
