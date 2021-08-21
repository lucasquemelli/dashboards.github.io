# dashboards.github.io
This is a repository about the creation of dashboards.

# Basic Plotly Charts: scatter, line, bar, bubble, histogram, pie and sunburst

Airline Reporting Carrier On-Time Performance Dataset

The Reporting Carrier On-Time Performance Dataset contains information on approximately 200 million domestic US flights reported to the United States Bureau of Transportation Statistics. 

The dataset contains basic information about each flight (such as date, time, departure airport, arrival airport) and, if applicable, the amount of time the flight was delayed and information about the reason for the delay. This dataset can be used to predict the likelihood of a flight arriving on time.

![image](https://user-images.githubusercontent.com/81119854/129193666-771f5ff5-68e0-4096-829d-662f40ce0007.png)

Read Data

![image](https://user-images.githubusercontent.com/81119854/129195282-4965f764-d864-4bb0-bfaa-3cc875ff37eb.png)

![image](https://user-images.githubusercontent.com/81119854/129195332-76eb704d-0670-428b-a22e-dad27307a351.png)

![image](https://user-images.githubusercontent.com/81119854/129195450-751ca23a-8423-44b3-84a4-fef9287f155f.png)

plotly.graph_objects

1. Scatter Plot

Idea: How departure time changes with respect to airport distance

![image](https://user-images.githubusercontent.com/81119854/129195619-d65c4f9c-8972-44d4-b1ec-52968ae92dde.png)

![image](https://user-images.githubusercontent.com/81119854/129195776-f474eef5-4a32-4598-8265-d8174133bc36.png)

2. Line Plot

Idea: Extract average monthly arrival delay time and see how it changes over the year.

![image](https://user-images.githubusercontent.com/81119854/129196093-80bfee50-1514-4317-b51f-2f8eed64a82d.png)
![image](https://user-images.githubusercontent.com/81119854/129196124-c43b7253-10ec-4999-a181-c0cc62eaca71.png)

To do:

![image](https://user-images.githubusercontent.com/81119854/129196185-4eac3eea-0fd0-4a5f-b223-92775a225c02.png)

![image](https://user-images.githubusercontent.com/81119854/129196248-6da0870d-ef86-4ee9-9c2d-37781016044c.png)

![image](https://user-images.githubusercontent.com/81119854/129196287-1a5a93b3-d294-45e3-8da3-1b827620b956.png)

plotly.express

1. Bar Chart

Idea: Extract number of flights from a specific airline that goes to a destination

![image](https://user-images.githubusercontent.com/81119854/129199256-6d1a8442-ada6-4f7c-ae86-547e4fad5d3c.png)

![image](https://user-images.githubusercontent.com/81119854/129199317-154d03f1-b13b-4249-b638-cd5a3d6ac0dc.png)

![image](https://user-images.githubusercontent.com/81119854/129199368-b0fe4a5d-192b-4480-a82c-ed7fa12c7ca4.png)

![image](https://user-images.githubusercontent.com/81119854/129199431-b869b7e2-2bc1-47ed-a922-2c209a2a3ca0.png)

2. Bubble Chart

Idea: Get number of flights as per reporting airline

![image](https://user-images.githubusercontent.com/81119854/129199602-1933b86a-c9ed-4a7d-a0fe-4096984abe1c.png)

![image](https://user-images.githubusercontent.com/81119854/129199682-1687642e-af02-4b7d-9542-5b53382ffe02.png)

![image](https://user-images.githubusercontent.com/81119854/129199718-43bf061e-c91d-4795-a4c4-7b135a04731f.png)

![image](https://user-images.githubusercontent.com/81119854/129199759-85cb573a-a4ac-4cdb-8a88-fa41b5a33704.png)

![image](https://user-images.githubusercontent.com/81119854/129199847-456a6b5e-5294-43db-b0df-673ec29d3f5c.png)

Histogram

Idea: Get distribution of arrival delay

![image](https://user-images.githubusercontent.com/81119854/129202303-f51419d3-cfa2-42a8-80f9-6619ef8436e4.png)

To do

![image](https://user-images.githubusercontent.com/81119854/129202416-8b6cc0e8-7509-4380-abd6-d25b75318b9d.png)

![image](https://user-images.githubusercontent.com/81119854/129202452-86a64e53-b245-4a40-bec3-e52d2a2a9b34.png)

![image](https://user-images.githubusercontent.com/81119854/129202497-191074d9-2673-4091-9323-a053ecd20d26.png)

Pie Chart

Idea: Proportion of distance group by month (month indicated by numbers)

![image](https://user-images.githubusercontent.com/81119854/129202660-85968f9d-bb78-4624-a159-016a2c46f6e5.png)

![image](https://user-images.githubusercontent.com/81119854/129202707-8678309c-6c91-442a-87d7-a3563dccf5ef.png)

Sunburst Charts

Idea: Hierarchical view in othe order of month and destination state holding value of number of flights

To do

![image](https://user-images.githubusercontent.com/81119854/129202873-09c1b2f0-1364-4358-be39-482136b7a5cb.png)

# Dash basics: HTML and core components using Jupyterlab

![image](https://user-images.githubusercontent.com/81119854/129276528-d01f9737-921d-4573-b2cc-8a8802638025.png)

Load the data

![image](https://user-images.githubusercontent.com/81119854/129276564-5172b1ef-0ae6-4b2c-9011-0cd69ffb9870.png)

![image](https://user-images.githubusercontent.com/81119854/129276626-7c068c95-9ab1-432c-b41b-2a067129ca6e.png)

![image](https://user-images.githubusercontent.com/81119854/129276657-67305a29-a751-4dda-a93c-0a086fc9c033.png)

![image](https://user-images.githubusercontent.com/81119854/129276709-32a6b3d3-6c29-41f5-8067-bc6eaa9b664f.png)

Proportion of distance group (250 mile distance interval group) by month (month indicated by numbers).

![image](https://user-images.githubusercontent.com/81119854/129276779-786f3a73-d8d5-44cd-a28c-34609cf0bcff.png)

![image](https://user-images.githubusercontent.com/81119854/129276802-38dc60b9-85ef-44b4-927d-4733378bfd69.png)

Let's start creating dash application

Theme
Proportion of distance group (250 mile distance interval group) by month (month indicated by numbers).

To do:

1.Import required libraries and create an application layout
2.Add title to the dashboard using HTML H1 component
3.Add a paragraph about the chart using HTML P component
4.Add the pie chart created above using core graph component
5.Run the app

Hints

![image](https://user-images.githubusercontent.com/81119854/129277193-edb3af17-ee00-43a2-b776-96790211f062.png)
![image](https://user-images.githubusercontent.com/81119854/129277219-c2bd4941-58ef-4f42-8504-0bb0699e75af.png)

![image](https://user-images.githubusercontent.com/81119854/129277292-f56efb40-94e9-4c36-9cf2-bcf4c98b3302.png)

![image](https://user-images.githubusercontent.com/81119854/129277356-27efc44a-12a9-46f1-91a5-0da4cc90ff7a.png)

![image](https://user-images.githubusercontent.com/81119854/129277438-400fa871-7451-49ef-b3af-5013bcc1d4b1.png)

![image](https://user-images.githubusercontent.com/81119854/129277463-15512ce3-4693-4475-bb0b-af144051e964.png)

# Dashboard aula House Rocket

![image](https://user-images.githubusercontent.com/81119854/130336839-3c0a0da1-aa9a-4733-a798-3b12451c0428.png)

![image](https://user-images.githubusercontent.com/81119854/130336849-42a3b3a9-9bd8-413a-b3ce-abb0e110c861.png)

