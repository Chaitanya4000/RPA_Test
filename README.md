# RPA_Test

Project Description:

> Bot is targeted to automate Consulta de licitaciones process.
> Bot navigates to provided webpage and apply given filters.
> Bot is then designed to scrap results if results are more than 0.
> For each scrapped result, respective files are downloaded to local folder path.

Technical Description:

> RPA bot is designed in UiPath 2019.12.0(CE)
> Input values can be provided and edited from the Config file which is provided in Json format at path: Data\Config.txt
> Framework is designed as per the process and is very stable to handle application and business exceptions.
> Main xaml of project is present at path: "RPA_Test\Main.xaml"
> Other xamls used in process are available in ‘Framework’ folder.
> Comments are added in a code to make code readable.
> Logs providing ‘info’ and ‘warn’ messages is added at respective steps.
> Naming conventions used for arguments is as given below:
In/Out_TypeOfArgument_NameOfArgument
For example: in_str_TypeOfContract
> Naming conventions used for variables is as given below:
TypeOfVariable_NameOfVariable
For example: str_StateName


