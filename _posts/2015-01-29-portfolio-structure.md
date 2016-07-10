---
category: Definition
path: '/definition'
title: 'Portfolios structure'

---

This method allows users to retrieve stuff.

### Request

* The headers must include a **valid authentication token**.

### Response

Sends back a collection of things.

 | Header1 | Header2 | Header3 |
 | --------| ------- |-------- |
 | cell1   | cell2   | cell3   |
 | cell4   | cell5   | cell6   |
 |:--------|:-------:|--------:|
 | cell1   | cell2   | cell3   |
 | cell4   | cell5   | cell6   |
 

```Status: 200 OK```
```{
    {
        id: thing_1,
        name: 'My first thing'
    },
    {
        id: thing_2,
        name: 'My second thing'
    }
}```

For errors responses, see the [response status codes documentation](#response-status-codes).
