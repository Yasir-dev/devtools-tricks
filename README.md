# Devtools tips and tricks

Collection of tips and tricks for leveraging Chrome DevTools

## Stoping the browser from redirect

```
//This will stop the browser from redirecting (helpful to view console log outputs before redirect)
window.addEventListener("beforeunload", function() { debugger; }, false);
```

## Check events for element

```
//All events
monitorEvents($0);

// particular event
monitorEvents($0, ['focus']);
```

## Get event listeners

```
getEventListeners($0);
```
