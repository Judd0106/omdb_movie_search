Here's a simplified `README.md` file tailored for users to run the project in JupyterLab:

---

## **Movie Information Lookup Application**

### **Overview**
The **Movie Information Lookup Application** is a Python program designed to help users search for detailed information about movies and TV series using the OMDB API. The project is implemented in a Jupyter Notebook, providing an interactive environment for running and modifying the code.

---

### **Features**
- Search for movies or TV series by title or IMDB ID.
- View detailed information, including release year, director, genre, plot, and ratings.
- Automatically save and revisit search history.

---

### **How to Use**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/movie-lookup-app.git
   cd movie-lookup-app
   ```

2. **Open in JupyterLab**:
   - Make sure JupyterLab is installed on your system.
   - Start JupyterLab in the project directory:
     ```bash
     jupyter lab
     ```
   - Open the `.ipynb` file in JupyterLab.

3. **Set Up API Key**:
   - Obtain a free API key from [OMDB API](http://www.omdbapi.com/).
   - Replace the placeholder `your_actual_api_key` in the notebook with your API key.

4. **Run the Notebook**:
   - Execute the cells in the notebook to interact with the application.

---

### **Requirements**
- **Python**: Version 3.6 or higher
- **JupyterLab**: For running the notebook
- **Dependencies**:
  Install the required library:
  ```bash
  pip install omdb
  ```

---

### **File Structure**
```
.
├── Movie_Lookup_Notebook.ipynb  # Jupyter Notebook for the application
├── movie_search_history.txt     # File to store search history
├── README.md                    # Project documentation
```

---

### **Acknowledgments**
- The [OMDB API](http://www.omdbapi.com/) for providing movie and TV series data.

---

Feel free to let me know if you'd like any additional tweaks!
