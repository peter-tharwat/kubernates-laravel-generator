# About

## Generate important laravel kubernates files

```
✅ nginx/values.yaml
✅ init.yaml
✅ namespace.yaml
✅ prod-env.yaml
✅ deploy.yaml
✅ ingress.yaml
✅ pvc.yaml
✅ service.yaml
```

## How to Use

```php
-d for domain name (example.com)
-n for name space (example) optional (use default namespace)
-i for ingress name (ingress-example) optional (generate unique name based on domain name)
```

```bash
wget -q -O generator.sh https://raw.githubusercontent.com/peter-tharwat/kubernates-laravel-generator/master/generator.sh ; chmod +x generator.sh ; ./generator.sh -d example.com -n default
# Replace example.com with your domain
```

# Thanks
Made With Love By [PeterAyoub](https://PeterAyoub.me/)