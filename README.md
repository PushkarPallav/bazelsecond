**🧱 Bazel + Java HelloWorld Project**

A minimal yet well-structured Java project built with Bazel demonstrating:

Bazel Bzlmod (MODULE.bazel)

Java binary targets

Modular package structure

Reusable utility classes

Clean, scalable layout (similar to real industry projects)

**📦 Project Structure**
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

**🚀 Build & Run**
**🔨 Build the project**

From the project root:

bazel build //src/main/java/com/example/project:hello_world

**▶️ Run the program**
bazel run //src/main/java/com/example/project:hello_world

**✅ Expected Output**
Pushkar
Some String

**🛠️ Requirements**

Bazel 7.5+

Java JDK 17+

Git (optional, for version control)
