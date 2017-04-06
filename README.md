# Answers to W3C TAG questions for SharedArrayBuffer

Questions from [here](https://www.w3.org/TR/security-privacy-questionnaire/).

3.1 - PII with SharedArrayBuffer has identical properties to existing
JavaScript.

3.2 - High value PII is handled with identical properties to JavaScript.

3.3 - SABs do not introduce new state that persists across sessions.

3.4 - SABs do not expose persistent, cross-origin state to the web.

3.5 - SABs do not expose any other data to an origin that it doesn’t currently
have access to. They are strictly same origin.

3.6 - SABs do not enable new script loading mechanisms.

3.7 - SABs do not enable new location access.

3.8 - SABs do not allow access to sensors.

3.9 - NOTE: SABs might allow pages to determine the number of cores available
on a system.

3.10 - SABs do not allow access to other devices.

3.11 - SABs do not allow UI control.

3.12 - SABs do not expose temporary identifiers.

3.13 - SABs are single origin, single process.

3.14 - SABs work identically in incognito mode.

3.15 - SABs do not persist data.

3.16 - NOTE: The ECMAscript spec does not include these sections.

3.17 - SABs do not allow downgrading security characteristics.
