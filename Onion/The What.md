# The What

As we said in the introduction, the concept of Onion Architecture is closely connected to two other architectural styles – Layered and Hexagonal. Similarly to the Layered approach, Onion Architecture uses the concept of layers, but they are a little different:

-   **Domain Model layer**, where our entities and classes closely related to them e.g. value objects reside
-   **Domain Services layer**, where domain-defined processes reside
-   **Application Services layer**, where application-specific logic i.e. our use cases reside
-   **Outer layer**, which keeps peripheral concerns like UI, databases or tests

Those layers when presented as circles, each wrapping around the previous one, form the famous “onion”:

![](https://dz2cdn1.dzone.com/storage/temp/4436217-kolka.png)