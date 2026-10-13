---
title: Custom Components Test
---
sdfasdf aaaaa

<TestBlock287 />

<ExampleThing header="Getting Started with Custom Components" />

<Docssss />

<Banner
  isInline={true}
  message="This component is only defined in v1.0"
  color="#118cfd"
  textColor="#ffffff"
  fontSize="14px"
  fontWeight="bold"
 />

<Steps name="quickstart">
  <Step title="Create an API key">
    Sign up for an Acme account and navigate to your API settings to generate a new API key.

    ```json Request
    POST https://api.acme.com/v1/keys
    ```
  </Step>

  <Step title="Authenticate your request">
    Include your API key in the Authorization header of your requests.

```javascript
const response = await fetch('https://api.acme.com/v1/data', {
  headers: {
    'Authorization': 'Bearer YOUR_API_KEY'
  }
});
```
  </Step>

  <Step title="Make your first API call">
    You&apos;re all set! Start making requests to the Acme API.
  </Step>
</Steps>
