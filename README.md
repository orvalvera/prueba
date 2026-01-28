# prueba

```mermaid
classDiagram
    class Aprobador {
        -nombre: String
        -limite: int
        -siguiente: Aprobador
        +aprobar(monto)
    }
    Aprobador --> Aprobador : siguiente
