# Dev Studio

This repo contains the content for tenants of Developer Studio.


## Directory structure

- /docs - all markdown files are to be placed in this directory
- /assets -  static assets like image etc here
- /config/document-explorer-definition.yaml: Provide document explorer structure for dev studio.  Also known as the ded (dead) file.
- ./docingore - companion file to the ded file.  use this to hide markdown files from showing up in the doc explorer and from being indexed & searchable
- /config/tenant_api.json: Tenant Provider API 
- /config/product_layout.yaml: Yaml spec for product layout page
- /reference/api-[document.version].yaml: Tenant APIs in OpenAPI 3.0 Spec

## Setup a new tenant

### Configure tenant.json

The main configuration file for everything.

DO NOT modify the structure.

DO update the sections that are needed.  Look for "REPLACE ME".  You can then replace the text for that field.
