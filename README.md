# activity-framework
Framework for building discord embedded activities.

## How to use
1. Install all dependencies
2. Fill in your apps details in `config.json`
3. Build the activity (`npm run build`, use `npm run build-dev` for faster development builds with source maps)
4. Generate localhost https certificates
    - You can use [mkcert](https://github.com/FiloSottile/mkcert/releases/) for this.
    - Place your localhost certificates under `activity-server/cert/` (Both `localhost-key.pem` and `localhost.pem` must be present)
5. Run the activity server (`npm start`)
6. Your built activity will be served on `https://localhost:3000`

If you have any further questions, feel free to ask them in my [discord server](https://discord.gg/DDg5Z7kZvs).