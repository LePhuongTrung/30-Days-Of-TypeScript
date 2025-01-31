# 30 Days Of TypeScript


| # Day |                                                                  Topics                                                                   |
| ----- | :---------------------------------------------------------------------------------------------------------------------------------------: |
| 01    |                                                           [Introduction](./readMe.md)                                                      |
| 02    |                                             [Basic Types](./02_Day_Basic_types/02_day_basic_types.md)                                      |
| 03    |                                       [Interfaces and Type Aliases](./03_Day_Interfaces/03_day_interfaces.md)                               |
| 04    |                                              [Enums](./04_Day_Enums/04_day_enums.md)                                                       |
| 05    |                                              [Functions](./05_Day_Functions/05_day_functions.md)                                           |
| 06    |                                          [Union and Intersection Types](./06_Day_Union_intersection/06_day_union_intersection.md)           |
| 07    |                                        [Type Guards and Type Assertions](./07_Day_Type_guards/07_day_type_guards.md)                        |
| 08    |                                        [Advanced Types](./08_Day_Advanced_types/08_day_advanced_types.md)                                   |
| 09    |                                            [Generics](./09_Day_Generics/09_day_generics.md)                                                |
| 10    |                                              [Modules](./10_Day_Modules/10_day_modules.md)                                                 |
| 11    |                                           [Namespaces](./11_Day_Namespaces/11_day_namespaces.md)                                           |
| 12    |                                      [Declaration Files](./12_Day_Declaration_files/12_day_declaration_files.md)                            |
| 13    |                                       [Decorators](./13_Day_Decorators/13_day_decorators.md)                                               |
| 14    |                                             [Mixins](./14_Day_Mixins/14_day_mixins.md)                                                     |
| 15    |                                                [Classes](./15_Day_Classes/15_day_classes.md)                                               |
| 16    |                                             [Interfaces vs Classes](./16_Day_Interfaces_vs_classes/16_day_interfaces_vs_classes.md)        |
| 17    |                                   [Error Handling](./17_Day_Error_handling/17_day_error_handling.md)                                       |
| 18    |                                             [Promises](./18_Day_Promises/18_day_promises.md)                                               |
| 19    |                                               [Async/Await](./19_Day_Async_await/19_day_async_await.md)                                    |
| 20    |                                  [TypeScript with React](./20_Day_TypeScript_with_React/20_day_typeScript_with_React.md)                   |
| 21    |                                 [TypeScript with Node.js](./21_Day_TypeScript_with_Node/21_day_typeScript_with_Node.md)                    |
| 22    |                           [TypeScript with Express](./22_Day_TypeScript_with_Express/22_day_typeScript_with_Express.md)                    |
| 23    |                                  [TypeScript with NestJS](./23_Day_TypeScript_with_NestJS/23_day_typeScript_with_NestJS.md)                |
| 24    |                          [Testing with TypeScript](./24_Day_Testing_with_TypeScript/24_day_testing_with_TypeScript.md)                     |
| 25    |       [Mini Project: Building a REST API](./25_Day_Mini_project_REST_API/25_day_mini_project_REST_API.md)                                  |
| 26    | [Mini Project: Creating a Chat Application](./26_Day_Mini_project_chat_app/26_day_mini_project_chat_app.md)                                |
| 27    |        [Mini Project: Todo List Application](./27_Day_Mini_project_todo_list/27_day_mini_project_todo_list.md)                             |
| 28    | [Mini Project: E-commerce Website](./28_Day_Mini_project_ecommerce/28_day_mini_project_ecommerce.md)                                       |
| 29    |    [Mini Project: Portfolio Website](./29_Day_Mini_project_portfolio/29_day_mini_project_portfolio.md)                                     |
| 30    |                      [Final Projects](./30_Day_Final_project/30_day_final_project.md)                                                      |

<div align="center">
  <h1> 30 Days Of TypeScript: Introduction</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/lephuongtrung/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>


<sub>Author:
<a href="https://www.linkedin.com/in/lephuongtrung/" target="_blank">Le Phuong Trung</a><br>
<small> July, 2024</small>
</sub>
### Credits
This project format was inspired by [Asabeneh's 30 Days Of JavaScript](https://github.com/Asabeneh/30-Days-Of-JavaScript). We are grateful for the contributions and templates provided by the open-source community.
</div>


- [30 Days Of TypeScript](#30-days-of-typescript)
- [📔 Day 1](#-day-1)
	- [Introduction](#introduction)
	- [Requirements](#requirements)
	- [Setup](#setup)
		- [Install Node.js](#install-nodejs)
		- [Browser](#browser)
			- [Installing Google Chrome](#installing-google-chrome)
			- [Opening Google Chrome Console](#opening-google-chrome-console)
			- [Writing Code on Browser Console](#writing-code-on-browser-console)
				- [Console.log](#consolelog)
				- [Console.log with Multiple Arguments](#consolelog-with-multiple-arguments)
				- [Comments](#comments)
				- [Syntax](#syntax)
			- [Arithmetics](#arithmetics)
		- [Code Editor](#code-editor)
			- [Installing Visual Studio Code](#installing-visual-studio-code)
			- [How to Use Visual Studio Code](#how-to-use-visual-studio-code)
	- [Adding JavaScript to a Web Page](#adding-javascript-to-a-web-page)
		- [Inline Script](#inline-script)
		- [Internal Script](#internal-script)
		- [External Script](#external-script)
		- [Multiple External Scripts](#multiple-external-scripts)
	- [Introduction to Data types](#introduction-to-data-types)
		- [Numbers](#numbers)
		- [Strings](#strings)
		- [Booleans](#booleans)
		- [Undefined](#undefined)
		- [Null](#null)
		- [Any](#any)
		- [Void](#void)
		- [Never](#never)
		- [Array](#array)
		- [Tuple](#tuple)
		- [Enum](#enum)
	- [Checking Data Types](#checking-data-types)
	- [Comments Again](#comments-again)
	- [Variables](#variables)
		- [Let](#let)
		- [Const](#const)
- [💻 Day 1: Exercises](#-day-1-exercises)
