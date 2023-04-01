# Piano Music Generation
### Description
The goal of the project is to generate piano music, inspired by classical piano compositions. The project also includes a classification part, the goal being to identify the composer of a excerpt from a piece in the dataset.

The compositions are retrieved with MIDI files, using web-scraping.

### Results
The resulting generated audio can be opened at [/generated_samples](https://github.com/timothewt/Piano_Music_Generation/tree/main/generated_samples)

### Technologies used
- PyTorch for the LSTMs and CNNs model
- BeautifulSoup for the web scraping / MIDI files retrieving

### How to use
Open the main file of the repo, [Music Generation](https://github.com/timothewt/Piano_Music_Generation/blob/main/Music_Generation.ipynb), and click on "Open in Colab" at the top of the file.

Note that the audio cannot be played through the notebook on GitHub.
