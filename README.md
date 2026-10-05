# Legalease-AI
import streamlit as st st.title("PocketSmart Al") income = st.number_input("Income Rs:", value=5000)  if st.button("Generate Plan"): st.write(f"Food: Rs. (income*0.5}") st.write(f"Studies: Rs. (income*0.3}") st.write(f"Savings: Rs. (income*0.2}")
