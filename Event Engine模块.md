```mermaid
classDiagram
class FileDescriptor {
  - inf fd_
}
class FileDescriptorCollection {
}
class EventEnginePosixInterface {
  - FileDescriptorCollection descriptors_
}
```
