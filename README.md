# Docker Build Failure: Missing Application Script
This repository demonstrates a common Dockerfile error: forgetting to copy the main application script into the image.
The initial `Dockerfile` results in a build failure because the `CMD` instruction attempts to execute a script that isn't present in the image.
The `Dockerfile.fixed` provides the corrected version.