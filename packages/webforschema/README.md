# Web for Schema

Format the website/feed as a schema

Special Thanks: [webforai](https://webforai.dev)

## Features
html,url,web feed in schema format. Formatting is done using llm (default: gemini flash 2).

## Installation
```bash
npm install webforschema
```

## Methods
### Guess the appropriate schema based on content 
- htmlToSchema(html: string): Schema
- feedToSchema(feed: string): Schema
- urlToSchema(url: string): Schema

### Convert the content to object based on schema
- htmlToObject(html: string, schema: Schema): object
- urlToObject(url: string, schema: Schema): object
- feedToObject(feed: string, schema: Schema): object