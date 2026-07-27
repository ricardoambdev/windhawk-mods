# Windhawk Mods

Mods para [Windhawk](https://windhawk.net/) — personalizações para o Windows 11.

## Índice

| Mod | Arquivo | Versão | Descrição |
|-----|---------|--------|-----------|
| Start Menu Size RA | `ra_start_menu_size_1.0.cpp` | 1.0 | Define tamanho customizado para o Menu Iniciar e busca do Windows 11 |

---

## Start Menu Size RA

**Arquivo:** `ra_start_menu_size_1.0.cpp`

Mod que permite ajustar a largura e altura do Menu Iniciar e do painel de busca no Windows 11.

### Funcionalidades

- Tamanho customizado para o Menu Iniciar (versão clássica e reformulada)
- Tamanho customizado para o painel de busca na taskbar
- Suporte a DPI scaling via `MulDiv`
- Compatível com `StartMenuExperienceHost.exe` e `explorer.exe`

### Configurações

| Setting | Tipo | Descrição |
|---------|------|-----------|
| `width` | int | Largura do Menu Iniciar (0 = padrão do sistema) |
| `height` | int | Altura do Menu Iniciar (0 = padrão do sistema) |
| `searchWidth` | int | Largura do painel de busca (-1 = padrão, 0 = usar `width`) |
| `searchHeight` | int | Altura do painel de busca (-1 = padrão, 0 = usar `height`) |

### Uso

1. Instale o [Windhawk](https://windhawk.net/)
2. Abra o Windhawk > "Desenvolvimento" > "Compilar mod do código fonte"
3. Selecione o arquivo `ra_start_menu_size_1.0.cpp`

---

## Sobre esta pasta

Repositório pessoal de mods Windhawk criados ou adaptados por [ricardoambdev](https://github.com/ricardoambdev).

Cada arquivo `.cpp` é um mod independente que pode ser compilado diretamente pelo Windhawk.
