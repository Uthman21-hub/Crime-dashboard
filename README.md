from PIL import Image

st.header("🧠 Well-being Trends in the UK (Census Data)")

# Load images
life_img = Image.open("life_satisfaction.png")
happy_img = Image.open("happiness.png")
anxiety_img = Image.open("anxiety.png")

st.subheader("📈 Life Satisfaction Over Time")
st.image(life_img, use_column_width=True)

st.subheader("📈 Happiness Over Time")
st.image(happy_img, use_column_width=True)

st.subheader("📈 Anxiety Over Time")
st.image(anxiety_img, use_column_width=True)

"Add well-being visualizations to dashboard"
