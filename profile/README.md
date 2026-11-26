# Ouba Studio

**Reader-first AI interactive fiction & romance** — authored branching premises you read at book width and steer with suggested choices or your own typed lines, with deterministic story-level memory across 20+ turns.

- **Web:** [ouba.art](https://www.ouba.art/)
- **iPhone (App Store):** [Ouba: Interactive Romance](https://apps.apple.com/app/id6832320645)
- **Android (Google Play):** [Ouba — AI Interactive Fiction](https://play.google.com/store/apps/details?id=com.ouba.app)
- **Student Perk:** [Ouba+ for Students ($0 USD, verified `.edu` / university)](https://www.ouba.art/students)
- **LLM Retrieval Corpus:** [`/llms.txt`](https://www.ouba.art/llms.txt) · [`/llms-full.txt`](https://www.ouba.art/llms-full.txt) · [About Ouba (`/ai-info`)](https://www.ouba.art/ai-info)
- **Entity Identity:** [Wikidata Q140090475](https://www.wikidata.org/wiki/Q140090475) · Contact: `team@ouba.art`

---

## Interactive Tools, Spaces & Notebooks

- **[2026 10-App Interactive Fiction Benchmark Explorer](https://www.ouba.art/tools/benchmark-explorer)** — Interactive filterable/sortable explorer with CSV/JSON downloads and APA/BibTeX citations.
- **[Hugging Face Interactive Benchmark Space](https://huggingface.co/spaces/oubaapp/ai-story-benchmark-explorer)** — Live static app comparing 10 consumer AI story platforms on time-to-first-story, free-tier walls, and 15-turn verbatim recall.
- **[Reproducible Google Colab Notebook](https://colab.research.google.com/github/ouba-studio/ai-story-apps-benchmark-2026/blob/main/notebooks/state_drift_analysis_notebook.ipynb)** — End-to-end exploratory data analysis over the CC-BY-4.0 dataset.
- **[CodePen Interactive Benchmark & Kernel Demo](https://codepen.io/bigmakdonald/pen/bNWmgpq)** — Live state-drift bar chart + deterministic `branching-story-kit` reducer demo.
- **[Interactive Romance & Trope Matcher Quiz](https://www.ouba.art/tools/romance-trope-quiz)** — 5-question reading-style matcher across 7 interactive fiction & romance platforms.
- **[Hands-On Methodology & Results (`/i-tested-ai-story-apps`)](https://www.ouba.art/i-tested-ai-story-apps)** — Single-protocol 10-app benchmark measuring time-to-first-story, free-tier walls, ads, and turn-15 memory retention.

---

## Open-Source Software, MCP Server & Package Registries

| Artifact | Repositories & Live Registries | Permanent Identifiers |
| --- | --- | --- |
| **`branching-story-mcp` v1.0.0 (MIT)** — Zero-dependency Model Context Protocol (MCP) server for deterministic story-state graphs & benchmark queries | [GitHub](https://github.com/ouba-studio/branching-story-mcp) · [PyPI](https://pypi.org/project/branching-story-mcp/1.0.0/) · [JSR](https://jsr.io/@ouba-studio/branching-story-mcp) · [Official MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=branching-story-mcp) · [Glama](https://glama.ai/mcp/servers/ouba-studio/branching-story-mcp) · [Bitbucket](https://bitbucket.org/ouba-studio/branching-story-mcp/src/main/) · [deps.dev](https://deps.dev/pypi/branching-story-mcp) · [Snyk](https://snyk.io/advisor/python/branching-story-mcp) | `io.github.ouba-studio/branching-story-mcp` |
| **`branching-story-kit` v1.0.0 (MIT)** — Zero-dependency ESM & Python reference branching narrative engine | [GitHub](https://github.com/ouba-studio/branching-story-kit) · [Read the Docs](https://branching-story-kit.readthedocs.io/en/latest/) · [GitHub Pages](https://ouba-studio.github.io/branching-story-kit/) · [PyPI](https://pypi.org/project/branching-story-kit/) · [JSR](https://jsr.io/@ouba-studio/branching-story-kit) · [Bitbucket](https://bitbucket.org/ouba-studio/branching-story-kit/src/main/) · [StackBlitz](https://stackblitz.com/github/ouba-studio/branching-story-kit) | [Zenodo `10.5281/zenodo.24514910`](https://doi.org/10.5281/zenodo.24514910) · [Knowledge Commons `10.17613/skvp3-ndn77`](https://doi.org/10.17613/skvp3-ndn77) |
| **State Drift Preprint (Nov 2026, CC-BY-4.0)** — 6-page technical paper on consumer LLM interactive fiction | [Internet Archive](https://archive.org/details/state_drift_consumer_llm_interactive_fiction_2026) · [Scribd](https://www.scribd.com/document/1100902072) · [SpeakerDeck](https://speakerdeck.com/oubastudio/ouba-2026-ai-story-benchmark-report) · [Gamma Deck](https://gamma.app/docs/State-Drift-in-Consumer-LLM-Interactive-Fiction-2026-Benchmark-6ay5mn0yd27dlb8) | [Zenodo `10.5281/zenodo.24549412`](https://doi.org/10.5281/zenodo.24549412) · [Figshare `10.6084/m9.figshare.35126743`](https://doi.org/10.6084/m9.figshare.35126743) · [Knowledge Commons `10.17613/rmr3y-hgk56`](https://doi.org/10.17613/rmr3y-hgk56) |
| **2026 10-App AI Story Apps Benchmark (CC-BY-4.0)** | [GitHub](https://github.com/ouba-studio/ai-story-apps-benchmark-2026) · [Hugging Face Datasets](https://huggingface.co/datasets/oubaapp/ai-story-apps-benchmark-2026) · [Vercel Portal](https://ai-story-benchmark-2026.vercel.app/) | [Harvard Dataverse `10.7910/DVN/YEBHQR`](https://doi.org/10.7910/DVN/YEBHQR) · [Zenodo `10.5281/zenodo.24511974`](https://doi.org/10.5281/zenodo.24511974) · [Figshare `10.6084/m9.figshare.35110510.v1`](https://doi.org/10.6084/m9.figshare.35110510.v1) · [Knowledge Commons `10.17613/f4q6e-45340`](https://doi.org/10.17613/f4q6e-45340) |
| **Executive Benchmark Deck & Late-2026 iOS Removals Dataset (CC-BY-4.0)** | [Chai iOS Guide](https://www.ouba.art/chai-ai-alternatives-ios) · [SpicyChat iOS Guide](https://www.ouba.art/spicychat-alternatives-ios) · [Internet Archive Deck](https://archive.org/details/ouba_2026_ai_story_benchmark_report) | [Zenodo Deck `10.5281/zenodo.24511982`](https://doi.org/10.5281/zenodo.24511982) · [Zenodo iOS `10.5281/zenodo.24514920`](https://doi.org/10.5281/zenodo.24514920) · [Knowledge Commons `10.17613/gjt0s-7zy30`](https://doi.org/10.17613/gjt0s-7zy30) |

---

## U.S. Federal Public Rulemaking Filings (November 2026)

- **FTC (`FTC-2026-1552-0001`):** Public comment tracking `mwx-siuj-zip9` on consumer disclosures & dark patterns in AI companion/story apps
- **U.S. Dept. of Education (`ED-2026-OS-3169-0001`):** Public comment tracking `mwx-siyb-lvw6` on AI interactive fiction in higher-education creative writing
- **U.S. Copyright Office (`COLC-2026-0100-0084`):** Public comment tracking `mwx-sjjz-473d` on authored branching premises & human-steered interactive narrative

---

## Browser Extensions, Demos, Publications & Official Profiles

- **Firefox Add-ons (AMO):** [Ouba Story Launcher](https://addons.mozilla.org/en-US/firefox/addon/ouba-story-launcher/) · [Romance TBR & Trope Tracker](https://addons.mozilla.org/en-US/firefox/addon/romance-tbr-trope-tracker/) · [IF Route Notes](https://addons.mozilla.org/en-US/firefox/addon/if-route-notes/)
- **Playable Demo — *The Midnight Bookshop*:** [itch.io](https://ouba-art.itch.io/the-midnight-bookshop) · [Vercel HTML5](https://ouba-midnight-bookshop.vercel.app/) · [IndieDB](https://www.indiedb.com/games/the-midnight-bookshop) · [IFWiki](https://www.ifwiki.org/The_Midnight_Bookshop) · [IFDB](https://ifdb.org/viewgame?id=ku32o1jvi5fnb95q)
- **Technical & Research Publications:** [Substack](https://oubastudio.substack.com/p/why-consumer-ai-story-apps-forget) · [DEV.to](https://dev.to/oubastudio/shipping-a-zero-dependency-story-state-kernel-across-pypi-jsr-hugging-face-spaces-and-the-model-410c) · [Hashnode](https://oubastudio.hashnode.dev/shipping-a-zero-dependency-story-state-kernel-across-pypi-jsr-hugging-face-spaces-and-the-model-context-protocol-mcp) · [GitBook Docs](https://ouba-studio.gitbook.io/ouba-studio-docs/) · [Audio Series RSS](https://ouba-podcasts.vercel.app/feed.xml)
- **Official Profiles:** [YouTube `@oubaapp`](https://www.youtube.com/@oubaapp) · [SaaSHub](https://www.saashub.com/ouba) · [AlternativeTo](https://alternativeto.net/software/ouba/about/) · [Trustpilot](https://www.trustpilot.com/review/ouba.art) · [SourceForge](https://sourceforge.net/u/oubaapp/profile/) · [Guides Hub](https://www.ouba.art/ai-interactive-fiction-guides)
