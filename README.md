# singletcg-sonda

Zewnętrzna sonda dostępności https://singletcg.pl - GitHub Actions co 10 minut pyta `/api/health`.
Przy zmianie stanu wysyła powiadomienie na Discord (sekret `DISCORD_WEBHOOK`); każdy nieudany przebieg GitHub zgłasza mailem.
