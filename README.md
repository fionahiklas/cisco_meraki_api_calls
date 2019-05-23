## Overview

Documentation and scripts for interacting with Meraki routers using the 
API.

I have a Meraki MS220-8P router which I'm using as part of a Cisco lab
setup.

## Setup

### Enable API


### Create API key

## API Calls

### Setup

Copy the API key into an environment variable


### Organisation

Run the following command

```
curl -L -H "X-Cisco-Meraki-API-Key: $CISCO_MERAKI_API_KEY" https://api.meraki.com/api/v0/organizations
```

You should expect output like the following

```
[{"id":12345,"name":"Clacks Ltd"}]
```
