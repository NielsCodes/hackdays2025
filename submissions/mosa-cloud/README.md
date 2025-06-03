# 🏆 Final Submission for mosa.cloud

## Project

Épicentre

## Project Description

<b>Épicentre</b> is your starting point in the La Suite ecosystem. It combines data from multiple apps and summarizes it into widgets with bite-sized, actionable information. Configure your dashboard simply by telling Épicentre which information is important to you.

<b>Examples</b>

- Summarize recent changes your coworkers have made to your files
- Summarize the most important conversations from your Matrix chats
- Extract action points from your meetings

## Contributors

<a href="https://github.com/nielscodes">@nielscodes</a>,
<a href="https://github.com/CasperHollemans">@CasperHollemans</a>,
<a href="https://github.com/rielzzapps">@rielzzapps</a>,
<a href="https://github.com/AleVale">@AleVale</a>

## Code base

<a href="https://gitlab.zzapps.nl/mosa.cloud/hackdays25">mosa.cloud Gitlab</a>

## Deliverables

<a href="https://demo.mosa.cloud">Live demo</a>
(Add screenshots (image, gif or video) and presentation deck to `/assets`)

## Key Achievements

- Customizable and personalized hub as entrypoint into the suite
- Summarize important missed conversations from Matrix
- Summarize updates other people made on your Docs documents
- Extract action points from Meet summaries

## Challenges Overcome

- Combining various data sources into a structured
- Prioritizing information for the end-user
- Finding non-intrusive solution that can hook into any number of other apps in the suite
- Efficiently fetching valuable data
- Docker Hub did not work :(

## Impact

- Greater user acceptance
- Unified experience of the La Suite platform, regardless of apps installed
- Clear place to find information; no more looking for what's important to you

## Next Steps

- Adding more widgets to add cross-application functionality
  - Suggest and automate actions such as create email based on Meet summary or plan meetings based on discussions in Matrix
  - Help prioritize work
- Improving the prioritization of notifications shown in the Épicentre
- Implement the La Suite MCP endpoints
- Full-text search, since not every action should be governed by LLMs
- Replace remote LLMs with Ollama (with GPU)
- Allowing third-parties to add arbitrary widgets for their users (would need to look into safe remote code execution)
- General cleanup
