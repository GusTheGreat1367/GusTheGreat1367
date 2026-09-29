```csharp
public Guid GetReturnedValue(Menu menu) // bugged, just everything is bugged,  
        {                                                         //               _  \ /  _
            if(selected)                                          //                \ (0) /
            {                                                     //                 (|#|)
                Guid retGuid = menu.children[index].id;           //               _/ (0) \_
```
