# AFG Dashboard

The idea of this project was to create a simple tool to visualize NDVI time series in different regions of Afghanistan (read from a CSV file).

2 different dashboards have been implemented: one with **Tableau** and one with **Streamlit**

## Usage

  ### Streamlit
  
 - To run it locally: 
 
Clone the repository to your local machine. 
Install all packages from `requirements.txt`.

Run 
```
python -m streamlit run mainScript.py
```
in the cmd

 - To open the app:  https://share.streamlit.io/juholland/afg_streamlit/main/mainScript.py
 
  ### Tableau 
 (Tableau license required)
 - To run it locally: 
 
 Download the folder from the SharedPoint ([AFG_Tableau](https://wfp.sharepoint.com/:f:/s/ClimateandEarthObservation/EsIMBQ07h2dJvVtOTfTC5dUBd-x-7nYly0liPtVt31MevQ?e=Y3WCgF)). Open `AFG_NDVI.twb` with Tableau Desktop
 
 - To open the app:  https://analytics.wfp.org/t/Public/views/AFG_NDVI/Dashboard?:showAppBanner=false&:display_count=n&:showVizHome=n&:origin=viz_share_link

 
 
## Status

We decided to keep the Tableau version. 
Project on hold since we don't have enough Tableau license for now




