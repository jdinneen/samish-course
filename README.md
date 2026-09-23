# Samish Bay, explained

A guided course and data explorer about shellfish-harvest closures in Samish Bay (Skagit County, Washington), 2008–2026.

- **Course:** https://jdinneen.github.io/samish-course/
- **Explorer:** https://jdinneen.github.io/samish-course/explorer.html

**Data** is embedded in the pages. It comes from Skagit County's closure calendar and river-sample load calculator, the 2020–2026 closure notices, and USGS stream gauge 12201500 (Samish River near Burlington). Every record and every number stated on the pages is re-checked against those raw files before release.

**The "Ask about the data" chat** calls a small Google Cloud Run service that uses Google's Gemini model. No API key or password is in these pages: the service authenticates with its own Google Cloud identity. It only answers requests from this site, and it limits how many questions a visitor, and the whole service, can ask.

This is a historical learning tool, not a forecast or shellfish-safety advice.
