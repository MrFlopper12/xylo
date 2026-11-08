# Xylo
Visual-first Fabric client for Minecraft 26.2 (Java 25).

## Build the jar
**Easiest (no setup):** push this folder to a GitHub repo -> Actions tab -> "build" -> download the `xylo-jar` artifact.

**Locally:** install JDK 25 + Gradle 9+, then run `gradle build`. Jar: `build/libs/xylo-1.0.0.jar`
(use the one WITHOUT `-sources`).

## Install / upload
Needs Fabric Loader 0.19.1+ and Fabric API. Drop the jar in `.minecraft/mods`, or upload to Modrinth
(set loader = Fabric, game version = 26.2, environment = client-side, dependency = Fabric API).
