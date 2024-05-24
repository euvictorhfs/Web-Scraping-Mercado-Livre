# About the company
Mercado Livre is a leading technology website for e-commerce and fintech solutions in Latin America for millions of users buying, selling, advertising, shipping and paying for products over the internet.

# About this project
In this project I carry out web scraping of computers throughout Brazil, extracting data from the Mercado Livre website, transforming it into quality data and loading it into a database. The analyzes are delivered on a dashboard with streamlit.

# About this analysis
Filters were applied to collect raw data to minimize the impact on extracting data from the server and focus on real results, considering: 
- Computers only (excluding all-in-one, mini PCs and others);
- Only new products (excluding refurbished and used);
- Only gaming products (focused on high processor and graphics performance);
- Affordable price range compatible with the project’s objective (between R$5,000.00 and R$15,000.00).

To further reduce the impact on data extraction load, we only selected the first 15 pages of the website.

You can access the filtered URL below:
https://lista.mercadolivre.com.br/informatica/pc-mesa/computadores/novo/e-gamer/_PriceRange_5000-15000_NoIndex_True
