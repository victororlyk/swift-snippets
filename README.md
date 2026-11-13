# Swift Snippets

Swift and SwiftUI snippets for the [Zed](https://zed.dev) editor. Snippets are scoped to Swift files.

Written by Viktor Orlyk.

## Install as a dev extension

1. Clone this repository.
2. In Zed, open the command palette and run `zed: install dev extension`.
3. Pick the cloned folder.

## Snippets

| Prefix     | Expands to                          |
| ---------- | ----------------------------------- |
| `view`     | SwiftUI `View` struct               |
| `preview`  | `#Preview` block                    |
| `state`    | `@State private var` property       |
| `binding`  | `@Binding var` property             |
| `button`   | `Button` with action                |
| `list`     | `List` with `ForEach`               |
| `afunc`    | `async throws` function             |
| `task`     | `Task` block                        |
| `codable`  | `Codable` struct                    |
| `guardlet` | `guard let` with early exit         |
| `iflet`    | `if let` optional binding           |
| `docatch`  | `do`-`catch` block                  |

## License

[MIT](LICENSE) © Viktor Orlyk
