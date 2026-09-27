# proyek1-eda-kelompok12
## Analysis Title
Descriptive Analysis of Air Quality in Yogyakarta, Indonesia using the 2021 Database
## Member of Group 12

M. Akbar Rizky Hidayat 5027261032

Dhafin Abhinaya Setyawan 5027261083

Jenifer Tri Fena Andhika 5027261123

## Topic

Air Quality in Yogyakarta, Indonesia (2021) <br> Hourly measurement of air pollution.

## Dataset Source
The data comes from the Yogyakarta Environmental Agency (Dinas Lingkungan Hidup Yogyakarta), which was processed and uploaded to Kaggle by Adhang MM at this link: `https://www.kaggle.com/datasets/adhang/air-quality-in-yogyakarta-indonesia-2021`. <br> The license is *Data files © Original Authors*.


## 3 Data Insights 
1. PM2.5 was the dominant pollutant (Critical Component) in almost every month. In March and June, PM2.5 accounted for 100% of the recorded pollution cases.<br>
2. No hour in 2021 was classified as worse than "Moderate" so overall, 2021's air quality appears consistently good. O3 data has substantial gaps: it is completely absent in July and August, and largely missing in June, September, and November.<br>
3. There is no clear pattern of higher pollution during morning or rush hours throughout the whole year, which is considered somewhat surprising, since traffic is typically expected to cause noticeable spikes. December's PM2.5 readings are unusual: 596 out of 642 recorded values are exactly 0, which is likely to be more broken sensors than genuinely clean air.

## How To Run The Notebook 
1. Open Anaconda Prompt.<br>
2. Activate the environment by typing 'conda activate statprob'.<br>
3. Navigate to the folder where the notebook and dataset are saved using the 'cd' command.<br>
4. Launch the application by typing: 'jupyter notebook'.<br>
5. Once Jupyter Notebook is open, locate, and open the group's '.ipynb' file.
6. Make sure the '.csv' dataset file (e.g., "01-jogja-jan-2021.csv") is in the exact same folder as the notebook file so the program can read the data successfully.<br>
7. Execute the code by clicking the **Run All** button, or run the cells one by one sequentially from top to bottom using **Shift + Enter**.
