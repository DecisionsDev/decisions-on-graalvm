# decisions-on-graalvm

The aim of this project is to demonstrate how to leverage GraalVM to run an IBM ODM decision service.

## GraalVM
GraalVM is a Java VM and JDK based on HotSpot/OpenJDK, implemented in Java. It supports additional programming languages and execution modes, like ahead-of-time compilation of Java applications for fast startup and low memory footprint. 
For more information on GraalVM visit their projet site at https://www.graalvm.org/

## GraalVM installation
Graal was included in HotSpot-based Java VM releases like OpenJDK from Java 9 through 15, but was removed in Java 16 for lack of use.[6] The jaotc command creates a Native Image. The experimental -XX:+EnableJVMCIProduct flag enables the use of Graal JIT.

The experimentation has been performed with the following configuration:
- openjdk version "11.0.10" 2021-01-19
- OpenJDK Runtime Environment GraalVM CE 21.0.0.2 (build 11.0.10+8-jvmci-21.0-b06)
- OpenJDK 64-Bit Server VM GraalVM CE 21.0.0.2 (build 11.0.10+8-jvmci-21.0-b06, mixed mode, sharing)


