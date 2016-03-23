# README

This repo contains custom git hooks.

## Hooks

### pre-receive

| type       | tools | language |
|------------|-------|----------|
| pre-receive | gitlab | ruby |


This Hook checks commit format message.   
Default pattern is:

> [TYPE] Subject  
> _blank line_  
> multiline body  

This hooks use default regex pattern: 

    /\[(FIX|FEATURE|CONF|TEST|DOC)\] [A-Z][^\n]+\n\s*\n[A-Z].+/ 
