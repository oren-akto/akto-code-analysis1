# Akto code analysis action

## Example usage

```yaml
- name: Akto code analysis
  uses: oren-akto/akto-code-analysis@v1
  with:
    AKTO_DASHBOARD_URL: 'http://a0e069e6fbc6d423da7cfafc05a602fa-185d242a0b83f61f.elb.ap-south-1.amazonaws.com:8080'
    AKTO_API_KEY: ${{ secrets.AKTO_API_KEY }}
    API_COLLECTION_NAME: juice_shop_demo
```
