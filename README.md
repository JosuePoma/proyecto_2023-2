# proyecto_2023-2
PROYECTO DE PROGRAMACION  AVAZADA 2023-II
import streamlit as st
import pandas as pd
import numpy as np

st.title("Titulo 2023")

df = pd.DataFrame(np.random.randn(1000,2) / [50,50] + [37.76, -122.4], columns=['lat', 'lon'])

st.map(df)
