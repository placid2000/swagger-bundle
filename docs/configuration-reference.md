# Configuration Reference

```yaml
# ./app/config/config_dev.yaml
swagger:
    version: '2.0'       # Swagger version
    info:
        title: 'My API'  # Required
        version: '1.0'   # Required
        description: 'My API Description'
    host: ~              # API Host
    base_path: ~         # API base path
    provides: []         # Default list of all content types the API provides (e.g. [application/json])
    consumes: []         # Default list of all content types the API consumes (e.g. [application/json])
    schemes: []          # Default list of all API Schemes (e.g. [http, https])
    
    annotations:
        bundles: []      # Required - list of bundles to search for annotations in
        paths:   []      # List of any paths to include in the search for annotations
        
    api_gateway: false   # Set to true to generate a AWS API Gateway schema for your API
```
