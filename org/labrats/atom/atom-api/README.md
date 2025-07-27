Atom API
--
This is the API for AtomInterface.

```gradle
// for forge minecraft
dependencies {
    ... dependicy ... 
    minecraftLibrary "org.labrats.atom:atom-api:API-0.1.0"

    // dependicy for atom
    minecraftLibrary "org.labrats:reflections:0.0.1"
    minecraftLibrary 'org.javassist:javassist:3.30.2-GA'
    compileOnly("org.projectlombok:lombok:1.18.38")
    annotationProcessor("org.projectlombok:lombok:1.18.38")

}

```
