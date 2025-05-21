# Lab8-Starter

Albert Ho

1. Graceful degradation and service workers are related because of how service workers can allow graceful degradation in web applications by acting as an extra layer between the browser and the network. If the network is poor, or fails to send a request, a service worker can intercept the request and provide a cached version (that it stored) as a fallback response. By introducing service workers, this would allow your app to still have functionality, maintaining usability and a smooth user experience. Moreover, these service workers would allow users to navigate your application when in poor conditions where network issues may be prevailent.