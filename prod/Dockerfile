FROM publiocavalcante/php81

ENV PORT=9000

# Switch to user
USER ${uid}:${gid}

CMD ["sh", "-c", "php artisan serve --host=0.0.0.0 --port ${PORT}"]
