## How do I install ts?

### 1. Clone the Repository
Open your terminal, go to your preferred directory, and run this command

```bash
git clone https://github.com/SamKurb/flash_cards.git
```

### 2. Import into Anki
Once the repository is cloned, follow these steps (note the notes are stored in csv format inside of .txt files):

1. Launch **Anki**.
2. Navigate to **File > Import** in the top menu (or press `Ctrl + I`).
3. Locate the `flash_cards` directory and select the .txt file for the deck you want.
4. In the import dialog:
    * Select the **Destination Deck**.
    * Ensure **"Update existing notes"** is selected if you are re-importing.
5. Click **Import**.


## How do I update if a change is made?

When new cards are added or existing ones are corrected in the remote repository, follow these steps

### 1. Pull Latest Changes
Navigate to the repository folder in your terminal and run:

```bash
git pull origin main
```

### 2. Re-import to Anki
Simply repeat the **Import** process described above. 


> **NOTE!!!** Anki uses the first field of a note as a "key." If the first field matches an existing card, Anki will update the content of that card without resetting your anki schedule

