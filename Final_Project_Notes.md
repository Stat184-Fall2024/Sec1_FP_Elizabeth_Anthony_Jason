- ++ **Go Back:**
	1. [[STAT 184 HW]]

<br>

### 1. Notes
##### 1.1. Tasks to Allocate
1. **Make a Plan to Work** (<u>In Class 12/6</u>)
	1. Due Dates: 
		1. Presentation on 12/13 (Friday)
		2. Submit Project on 12/18 (Wednesday)
		3. Submit Peer Review (Required!!) on 12/19 (Thursday)
2. **Plan:**
	1. ???

##### 1.2. Step 1: Figuring Out Data

1. [Completed] *Look up data sets* → https://www.kaggle.com/datasets/steve1215rogg/student-lifestyle-dataset
2. *Wrangle data sets*
3. *Exploratory data analysis*— Literally explore data sets: Summary = min, max, mean/median/quartiles, “create view of `head` (first 10 entries?)”
4. ! **Requirement:**  Code should **only** be found in a Code Appendix at the end for a PDF, not in the body of your report.
	1. ```{r codeAppend, ref.label=knitr::all_labels(), echo=TRUE, eval=FALSE}```

##### 1.3. Step 2: Compiling the Report
1. State your research questions and explain them.
2. Describe the provenance of your data. 
	1. Where did you get the data, who collected the data, for what purpose, who/what make up the cases, etc. 
3. Explain how your data meet the FAIR and/or CARE Principles.
	1. !! **FAIR Principles:** 
		1. **Findability**: Other researchers should be able to <u>find the data</u>
			1. ? i.e. <u>name files descriptively</u> based on the project
			2. EX ‘SocialAnxietyStudy2024_SurveyData.csv’
		2. **Accessibility**: Other researchers should be able to <u>access the data</u>, within reason
			1. ? Use <u>consistent and clear fine</u> naming conventions
			2. n Helps in searching and indexing files
		3. **Interoperability:** Data should use <u>standardized formats/terminologies</u>
			1. ? Organize project files in a <u>well-labeled folder</u> structure
			2. EX Main folder ‘SocialAnxietyStudy2024’
		4. **Reusability:** Data should include detailed metadata to <u>allow reuse</u>
			1. ? Add <u>keywords or tags</u> in file properties or metadata to enhance searchibility. 
			2. EX ‘social anxiety’, ‘psychological study’, ‘2024’ 
	2. !!  **CARE Principles:**
		1. **Collective Benefit:** Data should <u>support the well-being</u> of Indigenous communities, prioritizing social equity and inclusion. 
		2. **Authority to Control:** Indigenous people should have <u>governance over their data</u>, including control over access and usage. 
		3. **Responsibility:** Data practices <u>must respect Indigenous</u> rights, cultural values, and historical contexts. 
		4. **Ethics:** <u>Ensure ethical, transparent, and fair practices</u> that respect the diversity and values of Indigenous communities.
4. Describe what attributes (variables) you'll focus your analysis on
	1. *Note:* Mention if they are part of your data sets or if you created them out of your data sets.
5. Create multiple data visualizations (tables and figures) that assist both the team and readers in understanding the data.
    1. Data visualizations should show a variety of your skills and geometries.
    2. ~~**Optional**: If your research question/data make sense to do so, try creating a map.~~
    3. Data visualizations should be appropriately sized--not too small and not too big.
    4. Figures and Tables should have **appropriate captions and appropriately cross-referenced** in the body of your report.
    5. Your team must produce at least one table that is _not_ a display of raw data.
        1. i.e. Your team must produce at least one plot/graph.
        2. There should be narrative text (i.e. explanation of the plot/graph) helping readers to better understand what the visualization helps them to learn about the data and context.
    6. Your report should narrative text (beyond explaining tables and figures) that explains the context and helps the reader make sense of what is going on.
6. ?? **Optional:** For those who want to challenge themselves further, feel free to include a section on using other statistical methods such as hypothesis testing, regression, ANOVA, or machine learning--see Chapter 18 of the Data Computing eBook
