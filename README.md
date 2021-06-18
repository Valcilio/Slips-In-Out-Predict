# SLIPS IN & OUT PREDICT

Link to the streamlit app: https://share.streamlit.io/valcilio/deploy-repos/challenge2/webapp.py

![houses prices analytics](/home/valcilio/respos/intelie/portfolio/Slips in & out prediction (1).png)

## **PREMISES:**

This project is based in a company of Oil&Gas that need to be better organized but don't know how because need to know how much time will be take some activities.

One of this activities is when will be joined the slips in and when the slips will be joined out to predict how much time will take the extraction.

Besides that, is necessary to take some assumptions:


- **1** - The slips will be joined in approximately 26% of the time that the slips take to join out.
- **2** - The CEO believes that the company can get a growth about 20% in it net profit with a better organization.

## **Attributes List:**

| Attributtes    |                                    |
| -------------- | ---------------------------------- |
| WOBA.klbf      | Weight-on-Bit (surfice, average)   |
| TQA.ft.lbf     | Rotary Torque (surface, average)   |
| RPMA.rpm       | Rotary Speed (surface, average)    |
| HKLA.klbf      | Hookload (average)                 |
| DMEA.ft        | Depth hole (measured)              |
| DBTM.ft        | Depth bit (measured)               |
| BPOS.ft        | Block position (in ft)             |
| MFOP.%         | Mud flow out (percentual )         |
| MFIA.galUS/min | Mud flow in average (in galUS/min) |
| MDOA.ppg       | Mud density out (average)          |
| MDIA.ppg       | Mud density in (average)           |
| ROPA.ft/h      | Rate of penetration (average)      |
| DHWOB.klbf     | Downhole weight on bit             |
| DHTQ.ft.lbf    | Downhole torque                    |
| ECD.ppg        | Equivalent circulating density     |
| SPPA.psi       | Standpipe pressure (average)       |
| TIME.S         | Timestamp (in seconds)             |

## **Solution Plan:**

With the objective to help the company to be better organized will be make a predict of how much time is take to the slips be in and out with these following steps:

**1 -** Describe the data to get a better comprehension.

**2 -** Derivate new features from the existing features in the dataset.

**3 -** Analysis the data to product insights.

**4 -** Prepare the dataset to make the predicts with the selected algorithms.

**5 -** Translate and interpreter the error to transform the model result into business value.

**6 -** Deployment of the model with a way that allow the company to check new makes its own predictions.

With all the solution planned the item to show in the end was designed to be:

- The web application to the business people make his own predictions.
- Slides to explain the results of the project.

## **Next Steps**

How next steps is recommended the following actions:

- Reunion to explain the performance and utilities of the model;
- In the same reunion, explain how use the Web App to produce results;
-  Work in others models to turn more efficient other areas of this activity;
- Finalize the reunion speaking about some new features to get and improve the performance of the model;
  - Features Example:
    - Mud densities;
    - Torque informations;
    - Quality of employees who work with the activity of this model. 

## **Conclusion**

This project was created with the intuit to be possible help the company to predict how much time will be spent with the activity to 'slips in' and 'slips out' and the objective was concluded with a machine learning model with a MAPE of 0,03% and a deployment between the streamlit to be accessible to all person.

Following the next steps part is possible to instruct the business people to obtain insights with this model between utilize the web application and help them do their jobs more efficiently.

Besides that, this model can give a return of up to 20%, if we considering the MAPE we can see a return about 19% because this model can help the organization to make their preparations in advance.

Lastly, with this project's web application is possible to help the business people to develop their own insights using the model in real time.

## Learns

With this project my main learn was about data preparation techniques and teory, here I feel that I truly dominated the data preparation methods of rescaling and can utilize then better in another projects.

Besides that, this project treats of a very singular situation and has data that I can't see in each day of my life, then I judged that this project was able to open more my mind to another business situations.
