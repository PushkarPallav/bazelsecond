Bazel + Java HelloWorld Project

This repository contains a minimal Java project built with Bazel, showcasing modular structure and reusable utilities.

📦 Project Structure

bazelsecond/
├── MODULE.bazel
├── .gitignore
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── example/
│                   └── project/
│                       ├── HelloWorld.java
│                       ├── BUILD
│                       └── utils/
│                           ├── MyUtil.java
│                           └── BUILD

🚀 Build & Run

To build the project:

bazel build //src/main/java/com/example/project:hello_world

To run the binary:

bazel run //src/main/java/com/example/project:hello_world

Expected output:

Pushkar
Some String

🧪 Testing (Coming Soon)

JUnit integration planned for utility testing.

🛠️ Requirements

Bazel 7.5+

Java 17+

Git (for version control)

📚 About

Built by Pushkar Pallav as part of a hands-on journey into Bazel's module system and scalable Java workflows.
