# VODKA Panel

VODKA Control Panel for Cloudflare Workers.

## Panel URL
`/vodkapanel`

## First login
1. Open `/vodkapanel`.
2. First-run password: `admin`.
3. Set a new master password twice (minimum 8 characters).
4. Future logins use the master password.

## Storage
Bind the KV namespace as `VODKA_KV`.

Deploy: `npx wrangler deploy`
