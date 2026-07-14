<h2><code>$ whoami</code></h2>

```go
package main

type Aejkatappaja struct {
    Roles    []string
    Editor   string
    Terminal string
    OS       []string
    WM       []string
    Keyboard string
}

func New() *Aejkatappaja {
    return &Aejkatappaja{
        Roles: []string{
            "Software Engineer",
            "Open Source Contributor",
        },
        Editor:   "Neovim btw",
        Terminal: "Ghostty",
        OS: []string{
            "macOS",
            "Arch Linux",
        },
        WM: []string{
            "Yabai",
            "Hyprland",
        },
        Keyboard: "HHKB Pro Hybrid Type-S",
    }
}
```

### Highlights

<table>
  <tr>
    <td width="90" align="center" valign="middle">
      <img src="https://qwik.dev/logos/qwik-logo.svg" width="24" />
    </td>
    <td valign="middle">
      <strong>QwikDev/devtools</strong><br/>
      <a href="https://github.com/QwikDev/devtools/pull/97">feat(extension): browser extension for Chrome MV3 & Firefox MV2</a><br/>
      <sub>Component tree · State inspection · Element picker · Live renders</sub>
    </td>
    <td align="right" valign="middle">
     <a href="https://github.com/QwikDev/devtools/pull/97"><img src="https://img.shields.io/badge/Merged-8957e5?style=square&logo=git&logoColor=white" alt="Merged" /></a>
  </td>
  </tr>
</table>

---

### Articles

   <table>
    <tr>
       <td width="90" align="center" valign="middle">
        <img src="https://github.com/Aejkatappaja/swapbook/raw/main/assets/logo-mark.svg" width="38" />
      </td>
      <td valign="middle">
        <strong><a href="https://dev.to/aejkatappaja/why-i-proxy-the-app-instead-of-importing-the-components-5hn2">Why I proxy the app instead of importing the components</a></strong><br/>
        <sub>Storybook imports components in isolation, but hypermedia behavior lives in server routes. Swapbook is a reverse proxy in front of the running app, so real htmx interactions hit the actual backend handlers.</sub><br/>
        <sub>Code: <a href="https://github.com/Aejkatappaja/swapbook">github.com/Aejkatappaja/swapbook</a></sub>
      </td>
    </tr>
    <tr>
       <td width="90" align="center" valign="middle">
        <img src="https://www.postgresql.org/media/img/about/press/elephant.png" width="28" />
      </td>
      <td valign="middle">
        <strong><a href="https://dev.to/aejkatappaja/i-load-tested-my-side-project-and-postgres-said-no-33h0">My CI was green. At 150 connections, Postgres said no.</a></strong><br/>
        <sub>Load testing exposed an unbounded Go connection pool. Past Postgres' 100-client limit it rejected connections; capping the pool with SetMaxOpenConns cut failures to zero and p95 latency to 32ms.</sub><br/>
        <sub>Code: <a href="https://github.com/Aejkatappaja/go-gym">github.com/Aejkatappaja/go-gym</a></sub>
      </td>
    </tr>
    <tr>
       <td width="90" align="center" valign="middle">
        <img src="https://github.com/Aejkatappaja/phantom-ui/raw/main/.github/assets/logo-phantom.svg" width="64" />
      </td>
      <td valign="middle">
        <strong><a href="https://dev.to/aejkatappaja/your-design-systems-shadow-dom-breaks-skeleton-loaders-heres-the-fix-4de7">Your Design System's Shadow DOM Breaks Skeleton Loaders. Here's the Fix</a></strong><br/>
        <sub>Shadow DOM hides layout from skeleton loaders. A pierce-shadow attribute traverses open shadow roots and slot projections to measure the real painted elements.</sub><br/>
        <sub>Code: <a href="https://github.com/Aejkatappaja/phantom-ui">github.com/Aejkatappaja/phantom-ui</a></sub>
      </td>
    </tr>
    <tr>
      <td width="90" align="center" valign="middle">
        <img src="https://github.com/Aejkatappaja/go-ts-types/blob/main/assets/logo.svg" width="32" />
      </td>
      <td valign="middle">
        <strong><a href="https://dev.to/aejkatappaja/end-to-end-type-safety-between-go-and-typescript-10mf">End-to-end type safety between Go and TypeScript</a></strong><br/>
        <sub>Comparing ConnectRPC, OpenAPI, GraphQL and manual typing through one shared, branded domain.</sub><br/>
        <sub>Code: <a href="https://github.com/Aejkatappaja/go-ts-types">github.com/Aejkatappaja/go-ts-types</a></sub>
      </td>
    </tr>
    <tr>
       <td width="90" align="center" valign="middle">
        <img src="https://github.com/Aejkatappaja/phantom-ui/raw/main/.github/assets/logo-phantom.svg" width="64" />
      </td>
      <td valign="middle">
        <strong><a href="https://dev.to/aejkatappaja/i-built-a-web-component-that-generates-skeleton-loaders-from-your-real-dom-59ae">I built a Web Component that generates skeleton loaders from your real DOM</a></strong><br/>
        <sub>Automating skeleton screens by deep-cloning and styling the actual DOM tree into a loading state.</sub><br/>
        <sub>Code: <a href="https://github.com/Aejkatappaja/phantom-ui">github.com/Aejkatappaja/phantom-ui</a></sub>
      </td>
    </tr>
  </table>

---

### Bookshelf

<sub>· The Mythical Man-Month · Designing Data-Intensive Applications · System Design Interview · A Philosophy of Software Design<br/> · Clean Code · The Pragmatic Programmer · Computer Systems: A Programmer's Perspective · Code Complete, 2nd Edition</sub>
