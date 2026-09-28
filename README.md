# Analogue Clock

Analogue Clock widget (PowerShell).

## Opacity

The clock window supports an **opacity** argument so the widget can sit as a semi-transparent overlay on the desktop.

| Argument | Alias | Default | Allowed values |
|---|---|---|---|
| `-Opacity` | `-o` | `1.0` (fully opaque) | `0.05`–`1.0` |

The value is passed straight through to WinForms `Form.Opacity`.

### Examples

```powershell
# Fully opaque (default)
.\AnalogueClock.ps1

# Half-transparent
.\AnalogueClock.ps1 -Opacity 0.5

# Short alias
.\AnalogueClock.ps1 -o 0.35

# Positional
.\AnalogueClock.ps1 0.7
