# pistol

## Page

    message PageMessage {
        int64  PageNo = 1;
        int64  PageSize = 2;
        int64  Total = 3;
        string SortField = 5;
        string Sort = 6;
    }