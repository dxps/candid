## canDID

A truthful and frank digital identity provider that covers identity and access management, but also the new and promising DID related specs.

### Project Structure

Here is a quick walk through to some of the main folders and files:

- `bin` contains the compiled binaries, ready to be deployed on a production system.
- `cmd/api` contains application-specific code for running the API server.
- `internal` contains various packages used by the API, it's not for a public (re) use nor application-specific.
- `migrations` contains SQL files used for database migrations.
- `remote` contains configuration files and setup scripts for the production deployment.
- `Makefile` file contains recipes for automating common administrative tasks such as building binaries, and executing database migrations.
