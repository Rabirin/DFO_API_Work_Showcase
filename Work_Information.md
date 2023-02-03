## __Work Information__

#### <ins>Work Environment, Inputs/Outputs</ins>

* Programming Language/Kernel:              Python 3.9.13
* Integrated development environment (IDE): Microsoft VSCode with Python and Jupyter extensions
* Code Development File Format:             Interactive Python Notebook (*.ipynb)
* Data Source:                              dfcat API for character information, Neople API for items and characters images
* Output File Format:                       HTML Files

#### <ins>Work Objective</ins>

Output Objective: To generate outputs similar to dfcat in 3 areas:
 * Top 200 players summary of a class.
 * Top 200 players equipment statistic count.
 * One character equipment details.

Witch class is used in this work showcase.

Note: Considering that the extracted information will ultimately be used to build a website, the outputs are presented in simple HTML format. I personally am not an expert in HTML, hence please forgive any shortcomings present in the outputs. The focus of this work is the extraction of information from API and arrange them appropriately such that it resembles the kDNF community websites.

#### <ins>Files Dictionary</ins>

* File Name: "char_info_data_structure.html" <br>
Sample file for dfcat API character information data structure. The data structure is created manually in a HTML like format to provide easier navigation using the expand and collapse function of HTML tags. It is recommended to view the file that supports HTML tags. Notice that the API data can be parsed as JSON, and the data values can be accessed in dictionary and list like approach in Python.

* File Name: "RankingSummary_Witch.html" <br>
Output file for top 200 characters summary of the class witch. The output has close to full similarity shown in dfcat. <br>
The extracted data are arranged using HTML table tags. <br>
Original link: https://dfcat.net/rank/geniewiz

* File Name: "EquipmentCountSummary_Witch.html" <br>
Output file for top 200 characters equipment statistic count. It shows how many of the 200 characters are using a particular equipment. The output lacks the bar display and shows numbers only. It also shows the count of all equipment slots unlike one slot filtering in dfcat. <br>
The extracted data are arranged using HTML table tags. <br>
Original link: https://dfcat.net/rank/geniewiz (click on the statistic count button to view)

* File Name: "CharacterEqs_cain_ec362ecd3b3d2d9f213b5ea29dc72ab6.html" <br>
Output file for one character equipment details (other information such as status, buff, skills, etc not included). <br>
The character used has serverId "cain" and characterId "ec362ecd3b3d2d9f213b5ea29dc72ab6" <br>
The extracted data are arranged using HTML div tags. <br>
Original link: https://dfcat.net/character/cain/ec362ecd3b3d2d9f213b5ea29dc72ab6 (See equipment tab)
