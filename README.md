# Awesome Terminal Aesthetics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, frameworks, and libraries that make the terminal genuinely beautiful to build with and look at.

Not just functional — _delightful_. Every entry here earns its place through great DX, visual polish, or both.

---

## Contents

- [TUI Frameworks](#tui-frameworks)
- [Prompt & Input](#prompt--input)
- [Styling & Output](#styling--output)
- [CLI Tools with Great Aesthetics](#cli-tools-with-great-aesthetics)
- [Terminal Multiplexers & Shells](#terminal-multiplexers--shells)
- [Terminal Emulators](#terminal-emulators)
- [Fonts](#fonts)
- [Colour Schemes](#colour-schemes)
- [Showcases & Inspiration](#showcases--inspiration)

---

## TUI Frameworks

Build full terminal UIs with great ergonomics.

- [Ratatui](https://github.com/ratatui/ratatui) `rust` — Immediate-mode TUI library. Composable widgets, excellent docs, huge community.
- [Bubble Tea](https://github.com/charmbracelet/bubbletea) `go` — Elm-inspired TUI framework. Clean architecture, part of the Charm ecosystem.
- [Ink](https://github.com/vadimdemedes/ink) `ts` — React for CLIs. Components, hooks, and the full React mental model in your terminal.
- [Textual](https://github.com/Textualize/textual) `python` — CSS-like layouts, reactive state, and a live devtools panel. Stunning output.
- [OpenTUI](https://github.com/OpenTUI/opentui) `ts` — High-performance terminal rendering with a focus on visual fidelity.
- [FTXUI](https://github.com/ArthurSonzogni/FTXUI) `cpp` — Functional, declarative terminal UI in C++. Surprisingly pleasant DX.
- [tview](https://github.com/rivo/tview) `go` — Rich widget library built on tcell. Tables, forms, modals — all polished.
- [Cursive](https://github.com/gyscos/cursive) `rust` — Ergonomic TUI with a focus on composable views and clean event handling.
- [urwid](https://github.com/urwid/urwid) `python` — Mature, powerful console UI library. Great for complex layouts.
- [blessed](https://github.com/chjj/blessed) `js` — A curses-like library for Node.js with a high-level terminal interface.
- [Notcurses](https://github.com/dankamongmen/notcurses) `c` — Blistering-fast, visually rich. Supports sixel graphics, video, and Unicode art.
- [Lanterna](https://github.com/mabe02/lanterna) `java` — Text GUI library for Java. Remarkably approachable DX for the ecosystem.

## Prompt & Input

Libraries that make user input feel polished.

- [Clack](https://github.com/bombshell-dev/clack) `ts` — Effortlessly beautiful CLI prompts. The gold standard for onboarding flows.
- [Huh](https://github.com/charmbracelet/huh) `go` — Forms and prompts from the Charm team. Feels native and refined.
- [Enquirer](https://github.com/enquirer/enquirer) `js` — Stylish, intuitive prompts. Great for scripting interactive CLIs.
- [@inquirer/prompts](https://github.com/SBoudrias/Inquirer.js) `ts` — The classic, fully modernised. Modular, typed, and composable.
- [promptui](https://github.com/manifoldco/promptui) `go` — Interactive prompts with validation. Clean and idiomatic Go.
- [Survey](https://github.com/AlecAivazis/survey) `go` — Feature-rich interactive prompts. Excellent multi-select and autocomplete.

## Styling & Output

Make your CLI output look as good as a GUI.

- [Lip Gloss](https://github.com/charmbracelet/lipgloss) `go` — Declarative styling for terminal layouts. Borders, padding, colours, alignment.
- [Rich](https://github.com/Textualize/rich) `python` — Beautiful rich text, tables, progress bars, and syntax highlighting.
- [Chalk](https://github.com/chalk/chalk) `js` — The de facto terminal string styling library. Simple, chainable, fast.
- [Glamour](https://github.com/charmbracelet/glamour) `go` — Markdown rendering for the terminal. Gorgeous output with custom themes.
- [Colorette](https://github.com/jorgebucaran/colorette) `js` — Minimal, fast terminal colours. No dependencies, no nonsense.
- [Kleur](https://github.com/lukeed/kleur) `js` — The fastest Node.js library for ANSI colours. Tiny and chainable.
- [lolcat](https://github.com/busyloop/lolcat) `ruby` — Rainbow colouring for terminal output. Pure joy.
- [Figlet.js](https://github.com/patorjk/figlet.js) `js` — ASCII art text banners in your terminal. Great for CLI splash screens.
- [Boxes](https://github.com/ascii-boxes/boxes) `c` — Draw ASCII boxes around text. Classic terminal decoration.

## CLI Tools with Great Aesthetics

Tools you use every day that happen to look exceptional.

- [bat](https://github.com/sharkdp/bat) `rust` — A `cat` clone with syntax highlighting, line numbers, and git integration.
- [eza](https://github.com/eza-community/eza) `rust` — A modern `ls` with icons, colours, and tree view. Replaced exa.
- [delta](https://github.com/dandavison/delta) `rust` — Syntax-highlighted diffs for git. Transforms `git diff` into something beautiful.
- [lazygit](https://github.com/jesseduffield/lazygit) `go` — A simple terminal UI for git. Feels magical to use.
- [lazydocker](https://github.com/jesseduffield/lazydocker) `go` — The same lazygit treatment for Docker. Effortless container management.
- [gitui](https://github.com/extrawurst/gitui) `rust` — Blazing fast terminal-ui for git. Keyboard-driven and snappy.
- [btop](https://github.com/aristocratos/btop) `cpp` — Beautiful resource monitor. Smooth animations, themeable, and information-dense.
- [bottom](https://github.com/ClementTsang/bottom) `rust` — Customisable cross-platform graphical process/system monitor for the terminal.
- [Starship](https://github.com/starship/starship) `rust` — The minimal, blazing-fast, infinitely customisable prompt.
- [Zoxide](https://github.com/ajeetdsouza/zoxide) `rust` — A smarter `cd` command. Fast, minimal, and elegant.
- [fzf](https://github.com/junegunn/fzf) `go` — A command-line fuzzy finder. Deceptively powerful, universally useful.
- [fd](https://github.com/sharkdp/fd) `rust` — A simple, fast, and user-friendly alternative to `find`.
- [ripgrep](https://github.com/BurntSushi/ripgrep) `rust` — Recursively searches directories. Faster and friendlier than grep.
- [Gum](https://github.com/charmbracelet/gum) `go` — Shell script glamour. Declarative, beautiful shell interactions in one binary.

## Terminal Multiplexers & Shells

Environments that elevate the whole terminal experience.

- [Zellij](https://github.com/zellij-org/zellij) `rust` — A terminal workspace with a focus on UX and discoverability. Layouts, plugins, and a beautiful default config.
- [tmux](https://github.com/tmux/tmux) `c` — The classic multiplexer. Infinitely scriptable; the foundation of most terminal setups.
- [Nushell](https://github.com/nushell/nushell) `rust` — A new shell with structured data, pipelines, and stunning table output.
- [Fish](https://github.com/fish-shell/fish-shell) `cpp` — A smart and user-friendly shell. Autosuggestions, colours, and great defaults out of the box.

## Terminal Emulators

Emulators that take aesthetics seriously.

- [Ghostty](https://github.com/ghostty-org/ghostty) — Blazing fast, native, and visually refined. Exceptional font rendering.
- [WezTerm](https://github.com/wez/wezterm) — GPU-accelerated with deep Lua config. Ligatures, multiplexer, and beautiful defaults.
- [kitty](https://github.com/kovidgoyal/kitty) — GPU-based, highly extensible, with its own graphics protocol.
- [Alacritty](https://github.com/alacritty/alacritty) — The original GPU-accelerated terminal. Fast, minimal, config-driven.
- [Rio](https://github.com/raphamorim/rio) `rust` — A hardware-accelerated terminal with a focus on performance and modern typography.
- [iTerm2](https://github.com/gnachman/iTerm2) — The macOS terminal that set the bar. Split panes, profiles, shell integration, and tmux support.

## Fonts

Typefaces that make reading code in a terminal a pleasure.

- [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) — Patched fonts with thousands of icons. Essential for icon support in TUI tools.
- [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono) — Designed specifically for developers. Excellent legibility and ligatures.
- [Fira Code](https://github.com/tonsky/FiraCode) — Monospace font with programming ligatures. The classic choice.
- [Cascadia Code](https://github.com/microsoft/cascadia-code) — Microsoft's take on a coding font. Cursive italic variant is beautiful.
- [Monaspace](https://github.com/githubnext/monaspace) — A superfamily of fonts from GitHub Next. Five typefaces, one system.

## Colour Schemes

Themes that travel across your whole terminal stack.

- [Catppuccin](https://github.com/catppuccin/catppuccin) — Soothing pastel palette. Ports for everything: editors, terminals, TUI frameworks.
- [Rosé Pine](https://github.com/rose-pine/rose-pine-theme) — All natural pine, faux fur and a bit of soho vibes.
- [Tokyo Night](https://github.com/tokyo-night/tokyo-night-vscode-theme) — A clean, dark theme celebrating the lights of downtown Tokyo at night.
- [Kanagawa](https://github.com/rebelot/kanagawa.nvim) — Inspired by the colours of the famous painting by Katsushika Hokusai.
- [Gruvbox](https://github.com/morhetz/gruvbox) — Retro groove colour scheme. Warm, contrasty, and timeless.
- [Nord](https://github.com/nordtheme/nord) — An arctic, north-bluish colour palette. Clean and icy.
- [Dracula](https://github.com/dracula/dracula-theme) — A dark theme with vivid colours. One of the most ported themes in existence.
- [base16](https://github.com/tinted-theming/home) — A framework for building consistent themes across hundreds of apps.

## Showcases & Inspiration

Things that exist purely to make you go "wait, that runs in a terminal?".

- [Charm VHS](https://github.com/charmbracelet/vhs) — Record terminal GIFs from code. Perfect for README demos.
- [asciinema](https://github.com/asciinema/asciinema) — Record and share terminal sessions. The standard for terminal screencasting.
- [pipes.sh](https://github.com/pipeseroni/pipes.sh) — Animated pipes in your terminal. A classic screensaver reimagined.
- [tty-clock](https://github.com/xorg62/tty-clock) — A simple digital clock for the terminal. Minimal and satisfying.
- [cmatrix](https://github.com/abishekvashok/cmatrix) — The Matrix rain effect. The original terminal eye candy.
- [cbonsai](https://github.com/mhum/cbonsai) — A bonsai tree that grows in your terminal. Oddly meditative.

---

## Contributing

This list is opinionated by design. If you have a suggestion, open an issue with a brief note on why it fits the _aesthetics_ bar — not just utility.
