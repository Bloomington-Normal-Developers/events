# Bloomington-Normal Developer Events

This repo contains a JSON file of all events for Bloomington-Normal Developers. The current structure of an event is as follows (subject to change):

```typescript
type Event = {
  title: string;
  date: string;
  startTime: string;
  endTime: string;
  details: string;
  location: string;
  address: string;
};
```
