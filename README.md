ftClient
========

A simple Google Fusion Tables client

###Usage###

To perform an AJAX GET to retrieve data from a Google Fusion Table:
```javascript
ftClient.query(queryObject, success, error)
```
where `queryObject` is an object with the (optional) query parameters:
```javascript
{
    select : ['array','of','column','names','to','retrieve'],
    where : 'where clause',
    orderBy : 'name of the column to order by',
    offset : 0    // Resultset offset,
    limit : 100   // Resultset limit
}
```