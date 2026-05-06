# EnergyFlux

Source for **EnergyFlux**, a blog by Chennan Li, PhD, PE &mdash; notes on energy, AI infrastructure, and where they converge.

**Live site:** _(add GitHub Pages URL here once enabled)_

## Posts

| Date | Title |
|------|-------|
| May 2026 | [Sizing distributed AI inference data centers at industrial sites](posts/02-sizing-distributed-inference-data-centers/) &mdash; Part 2 |
| April 2026 | [Turning industrial safety buffers into AI inference sites](posts/01-ai-inference-buffers/) &mdash; Part 1 |

## Structure

```
.
├── index.html                              # Landing page with post list
├── posts/
│   ├── 01-ai-inference-buffers/
│   │   ├── index.html                      # Blog post 1
│   │   └── _sources/                       # Figures and images
│   └── 02-sizing-distributed-inference-data-centers/
│       └── index.html                      # Blog post 2 standalone HTML
├── .nojekyll                               # Disables GitHub Jekyll processing
└── README.md
```

The `.nojekyll` file is required so that GitHub Pages serves the `_sources/` folders as-is (Jekyll would otherwise skip underscore-prefixed directories).

## About the author

Chennan Li, PhD, PE, writes about energy systems, AI infrastructure, and industrial deployment constraints.

- Medium: [@chennanli](https://medium.com/@chennanli)
- LinkedIn: [chennanli](https://www.linkedin.com/in/chennanli/)

## License

All content &copy; Chennan Li. Figures and prose may be cited with attribution.
