# JsonPowerdb-project

PUT
{
    "token": <"connection-token">,
    "cmd": "PUT",
    <<"dbName": <"database-name">,>>
    <<"rel": <"relation-name">,>>
    <<"colsAutoIndex": <boolean-value>,>>
    <<"templateStr": <jsonTemplateStr>,>>
    "jsonStr": <jsonDataStr>
}
  
  
  Get
  
  {
"token" : "608862677|6881615563076535601|608862582",
        "select":{"cols" : "*"},
        "from" : "Employee-DB|Employee",
        "createTime":true,
        "updateTime":true,
        "where" :[
                [
                        [ "Employee-DB|Employee.permanent_address",
                                "==",
                                {"value" : "Vijay nagar"}]
                        ],
                [
                        [ "Employee-DB|Employee.present_address",
                                "==",
                                {"value" : "Vijay nagar"}]
                        ]

                ],
        "limit" : [20, 0]
}
