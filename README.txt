1. Replace panel.example.com in Caddyfile with your domain.
2. Point that domain DNS A record to your server IP.
3. Open ports 80 and 443.
4. Run: docker compose up -d
5. Visit https://your-domain.example
This bundle hosts the panel and puts it behind Caddy HTTPS. It does not start or control game servers; that requires server APIs/backend integration.
