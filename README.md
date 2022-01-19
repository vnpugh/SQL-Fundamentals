# SQL-Fundamentals
<h1>Analyzing Country Profiles With SQL</h1>
<h2>Introduction</h2>
<p>This project utilizes data from the CIA World Factbook, a compilation of statistics about the countries on earth. The goal of this project is to demonstrate how to analyze country profiles with basic SQL queries.</p>

<h2>Project Overview</h2>
<p>The CIA World Factbook contains provides basic intelligence on the history, people, government, economy, energy, geography, environment, communications, transportation, military, terrorism, and transnational issues for 266 world entities. This project will focus on analyzing demographic and country profile information. SQL queries are used to pull the data from the 'Facts' table in the factbook.db database. Below, are descriptions for some of the columns in the table:</p>
<ul>
<li>Name - the name of the country.</li>
<li>Area - the country's total area (both land and water).</li>
<li>area_land - the country's land area in square kilometers.</li>
<li>area_water - the country's water area in square kilometers.</li>
<li>Population - the country's current population.</li>
<li>population_growth - the country's population growth as a percentage.</li>
<li>birth_rate - the number of births per year per 1,000 people.</li>
<li>death_rate - the number of deaths per year per 1,000 people. </li></ul>

<h2>Getting Started</h2>
<p> In this project, SQLite is used as the database management system (DBMS). The code below is used to connect Jupyter Notebook to the CIA factbook.db database:</p>

