# Tame-The-SurveyMonkey
Program for Collecting All Survey Information From SurveyMonkey API. I wrote this program to collect the survey ids, responses, possible responses, headers, and subquestions from the SurveyMonkey API. Since the API is rather difficult to work with due to its nested JSON formatting, I created this program to populate data frames with all the info that I wanted and then created the option to populate a MySQL database with these data frames as well. This program IS A TEST PROGRAM, it has worked for me hundreds of times, but I have only tested it on a total of 85 surveys and 296,000 individual response rows, thus the speed at which this will run at scale is slow. In addition, this is currently only working for surveys with up to 900 responses. If you wish to use this program for surveys that are longer than 900 responses, you can easily amend the code in the responses collector, or you can message me and I can add in the amount of responses that you need. Please let me know if this is helpful to you in any way and how I might be able to optimize the code for scalability and speed. My hope here is to allow people to use the SurveyMonkey API in a less painful way, and to get their survey data into csv files, data frames, or SQL databases in an easy manner without ripping your hair out. My email is fultoncannon@gmail.com if you want to get in touch. 
