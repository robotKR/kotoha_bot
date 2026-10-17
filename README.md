# kotoha-bot

Archived versions of the Kotoha Twitter bot, from 1.1.2 through 1.1.7.
Each version is stored in its own directory. `acsesskey` contains the OAuth
credential helper.

Credentials are not included. Configure the environment variables listed in
`.env.example` before running a version's `main.py`. A `.env` file must be loaded
into the process environment by your launcher; do not assume automatic loading.
For the credential helper, copy `acsesskey/config.example.py` to
`acsesskey/config.py` and supply your credentials locally.

For Docker, pass credentials at runtime with `--env-file`; they are not baked
into the image. These archived dependencies and external API integrations have
not been verified against current services.
