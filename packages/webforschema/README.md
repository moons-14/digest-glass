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
- htmlToSchema(html: string): string
- feedToSchema(feed: string): string
- urlToSchema(url: string): string

### Convert the content to object based on schema
- htmlToObject(html: string, schema: Schema): object
- urlToObject(url: string, schema: Schema): object
- feedToObject(feed: string, schema: Schema): object