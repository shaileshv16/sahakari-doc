**BBPS Bill Payments**
::: mermaid
 graph LR;
    A[Sahakari App] 
    A --> C{Dashboard}
    C-->H[Bill Payments]
    H-->G[Bill Category]
    G-->I[Biller]
    I-->J[Bill Details]
    J-->K[Payment]
    K-->L[Success]
    K-->M[Failed]
:::


**BBPS Complaints**

::: mermaid
 graph LR;
    A[Sahakari App] 
    A --> C{Dashboard}
    C-->H[Bill Payments]
    H-->G[Bill Category]
    G-->I[Complaint Register]
    I-->J[Add New Complaint]
    J-->K[Submit]
    K-->L[Success]
    K-->M[Failed]
    G-->N[Complaint Track]
:::

