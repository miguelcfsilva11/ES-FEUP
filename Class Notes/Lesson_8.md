#  Mobile Technologies

## Flutter

Flutter is an open-source application development kit created by Google. It uses Dart as it programming language and runtime library.

Dart is a **functional** and **object-oriented** language. It is strongly-typed.
In Dart *everything is an object*.

### Flutter has a **layered** architecture:

- **Flutter Framework**: the available code, although developer interface Main app code only uses *Material* and *Widgets* to create any application (*everything is a widget*)
- **Flutter Engine**: set of primitives used by framework layer (low-level implementation)
- **Embedder**: code that interfaces with the native OS. Allows the application to run on top of a native app, deals with messages and notification setup.

Flutter application is structured as a tree of objects (based on *composition*).