# EnergyFlux

Source for **EnergyFlux**, a blog by Chennan Li, PhD, PE &mdash; notes on energy, AI infrastructure, and where they converge.

**Live site:** [chennanli.github.io](https://chennanli.github.io/)

## Posts

| Date | Title |
|------|-------|
| April 2026 | [Turning industrial safety buffers into AI inference sites](posts/01-ai-inference-buffers/) &mdash; Part 1 |

## Structure

```
.
├── index.html                              # Landing page with post list
├── posts/
│   └── 01-ai-inference-buffers/
│       ├── index.html                      # Blog post 1
│       └── _sources/                       # Figures and images
├── .nojekyll                               # Disables GitHub Jekyll processing
└── README.md
```

The `.nojekyll` file is required so that GitHub Pages serves the `_sources/` folders as-is (Jekyll would otherwise skip underscore-prefixed directories).

## About the author

Chennan Li is a chemical engineer and licensed Professional Engineer with experience across refining, petrochemicals, wastewater treatment, and power generation. This blog explores practical questions at the intersection of industrial operations and the buildout of AI compute.

- Medium: [@chennanli](https://medium.com/@chennanli)
- LinkedIn: [chennanli](https://www.linkedin.com/in/chennanli/)

## License

All content &copy; Chennan Li. Figures and prose may be cited with attribution.
