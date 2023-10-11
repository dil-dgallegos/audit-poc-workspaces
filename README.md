# AUDIT POC WORKSPACES

This is a monorepo project created with workspaces. The front-end is located in `apps/client`, the back-end is located in `apps/server`, and there are two libraries: `apps/interfaces` and `apps/i18n`.

This project uses `pnpm` as its package manager. The following scripts are available:

- `dev:client`: Runs the development server for the client-side code.
- `dev:server`: Runs the development server for the server-side code.
- `dev`: Runs both the client and server development servers in parallel.
- `build:client`: Builds the client-side code for production.
- `build:server`: Builds the server-side code for production.
- `build`: Builds both the client and server code for production.

You can run any of these scripts by running `pnpm run <script-name>` in your terminal.
