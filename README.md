# jotadlabs.github.io

Public GitHub Pages site for **JOTAD Labs** — privacy policies and support pages for our mobile games.

## Live URLs

### Privacy Policies
| Game | URL |
|------|-----|
| Bloomlings | https://jotadlabs.github.io/privacy/bloomlings/ |
| Velocity Vandal | https://jotadlabs.github.io/privacy/velocityvandal/ |
| SmashBlocks | https://jotadlabs.github.io/privacy/smashblocks/ |
| FaultRunner | https://jotadlabs.github.io/privacy/faultrunner/ |
| AbyssalFall | https://jotadlabs.github.io/privacy/abyssalfall/ |

### Support Pages
| Game | URL |
|------|-----|
| Bloomlings | https://jotadlabs.github.io/support/bloomlings/ |
| Velocity Vandal | https://jotadlabs.github.io/support/velocityvandal/ |
| SmashBlocks | https://jotadlabs.github.io/support/smashblocks/ |
| FaultRunner | https://jotadlabs.github.io/support/faultrunner/ |
| AbyssalFall | https://jotadlabs.github.io/support/abyssalfall/ |

## Structure

```
privacy/
  bloomlings/index.md
  velocityvandal/index.md
  smashblocks/index.md
  faultrunner/index.md
  abyssalfall/index.md
support/
  bloomlings/index.html
  velocityvandal/index.html
  smashblocks/index.html
  faultrunner/index.html
  abyssalfall/index.html
_config.yml
```

Privacy policies are Jekyll Markdown rendered with the Minima theme.
Support pages are self-contained HTML with inline CSS (dark theme).

## Adding a New Game

1. Create `privacy/[gamename]/index.md` — copy an existing policy and update game name, services, and purchase list
2. Create `support/[gamename]/index.html` — copy an existing support page and update game name and privacy URL
3. Update this README
4. `git push` — GitHub Pages publishes within ~1 minute

## Contact

dev@jotadlabs.com
