# Notes
- Jython is a language runtime with no web UI. `docker-compose.base44.yml` builds it with `gradle jar` (output in `build2/libs`) and serves a status page generated from real Jython output on port 3000.
- First boot takes a few minutes (Gradle build). No secrets needed.
