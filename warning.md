# Warning: Hardcoded Credentials

Hardcoding passwords, API keys, or other secrets in configuration files is a severe security risk. Such credentials can be easily exposed if the repository is public or if source code is shared.

## Best Practices
- Use environment variables for sensitive data.
- Employ secret management tools (e.g., HashiCorp Vault, AWS Secrets Manager).
- Never commit secrets to version control.
- Regularly audit your code for accidental credential leaks.

This repository contains examples of insecure patterns for educational purposes only. Do not use these patterns in production.