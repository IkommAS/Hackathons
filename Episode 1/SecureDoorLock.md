# What?
Be able to unlock a doorlock by interacting with Ikomm gateway.



```mermaid
graph LR
    F[WebApp] -->|Command| A(Ikomm Connect)
    A[Ikomm Connect] -->|Update| F(WebApp)
    A[Ikomm Connect] --> |Command| B(IOT-Gateway) --> C(Smartlock)
    C[Smartlock] --> B(IOT-Gateway) -->|Update| A(Ikomm Connect)
```
