# Github Docker Build Action

This action init Environment variables for Windows runners.

## Example usage 

```
- uses: webjet/action-kubernetes-init-windows@v1
  with:
    env-json-base64: ${{ secrets.JSONDATA64 }}

```

