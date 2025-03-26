# How to Learn and Use These Keybindings in LazyVim 
## Step 1: Understand Modes in Vim

Vim has different modes, and keybindings work differently in each:

- **Normal Mode (n)** – Default mode for navigation and editing commands
- **Insert Mode (i)** – Used for typing text
- **Visual Mode (v)** – Used for selecting text
- **Command Mode (:)** – Used for executing commands

To enter Normal Mode, press `Esc`.

## Step 2: Essential Keybindings and How to Use Them

### 1. Delete & Paste Without Affecting Register
- `x` → Deletes a character without saving it to clipboard
- `<Leader>p` → Pastes from register 0 (last yanked text)  
  Press `\p` (default `<Leader>` is `\`, but you can change it)
- `<Leader>P` → Pastes above the cursor  
  Press `\P`
- `dw` → Deletes a word backward without copying  
  Press `dw` in normal mode

### 2. Increment & Decrement Numbers
- `+` → Increases the number under the cursor (`Ctrl-a`)
- `-` → Decreases the number under the cursor (`Ctrl-x`)

### 3. Selecting Text
- `<C-a>` → Selects all text  
  Press `Ctrl-a` in normal mode

### 4. Tabs & Splits
- `te` → Opens a new tab  
  Type `te` in normal mode
- `<Tab>` → Moves to the next tab  
  Press `Tab`
- `<S-Tab>` → Moves to the previous tab  
  Press `Shift-Tab`
- `ss` → Splits window horizontally  
  Type `ss` in normal mode
- `sv` → Splits window vertically  
  Type `sv` in normal mode

**Window Movement:**
- `sh` → Move left (`Ctrl-w h`)
- `sj` → Move down (`Ctrl-w j`)
- `sk` → Move up (`Ctrl-w k`)
- `sl` → Move right (`Ctrl-w l`)

### 5. Resizing Windows
- `<C-w><Left>` → Shrinks the window
- `<C-w><Right>` → Expands the window
- `<C-w><Up>` → Increases height
- `<C-w><Down>` → Decreases height

### 6. Diagnostics (Errors & Warnings)
- `<C-j>` → Jump to the next error or warning  
  Press `Ctrl-j`

## Step 3: Practicing These Bindings

Open a file in LazyVim:

```sh
nvim myfile.txt
```

Try each keybinding above:

- Open a tab with `te`
- Split windows with `ss` and `sv`
- Move between splits with `sh`, `sj`, `sk`, `sl`

- Resize splits with `<C-w><left/right/up/down>`

- Try pasting with `<Leader>p` (`\p`)

- Jump to errors with `<C-j>`

