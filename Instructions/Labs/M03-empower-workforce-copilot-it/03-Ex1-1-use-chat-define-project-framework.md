# Exercise 1 - Task 1: Use Copilot Chat to define the project framework

## Scenario

This task demonstrates how Copilot Chat can accelerate the early stages of project planning and ensure alignment across IT, business, and leadership teams.

You’re the lead member of Boulder Innovation’s IT team responsible for implementing the Network Modernization and Security Upgrade Project. Before any work can begin, the CIO wants a clear understanding of the project’s purpose, goals, deliverables, and stakeholders. The CIO tasked your team with gathering and synthesizing all relevant information from project documents, email threads, and chat logs to create a coherent project framework that guides the team’s planning and execution.

To complete this task, you plan to use Microsoft 365 Copilot Chat to gather and synthesize information from multiple sources across their organization. In this scenario, Copilot Chat acts as a bridge between fragmented data—emails, Teams discussions, and project documents—allowing your IT team to quickly generate a unified view of project requirements and stakeholder expectations.

## Lab Overview

In this hands-on lab, you will use Microsoft 365 Copilot Chat to gather and synthesize information from multiple project-related sources to create a structured project framework. You will analyze documents, emails, and Teams conversations, identify key stakeholders and requirements, and generate a leadership-ready summary. You will also enhance the resulting document with visuals and strategic Q&A content to support executive planning and decision-making.

## Task 1: Use Copilot Chat to define the project framework

In this task, you will use Microsoft 365 Copilot Chat to consolidate information from multiple project documents related to Boulder Innovation's Network Modernization and Security Upgrade Project. You will generate a project framework, export the results to Word, enrich the document with visuals, and create executive-focused Q&A content.

1. On the **Microsoft 365** home page, over the Microsoft 365 Copilot Chat verify the **Work** tab is selected. 

   ![](../media/Module3/E1T1S1.png)

1. In **Copilot Chat** on the web, the response mode selector lets you control how much time and reasoning Copilot uses when answering your prompt. You can leave it set to **Auto** (the default option) so Copilot balances speed and depth for you, or choose a faster or more in depth response style depending on the task.

1. When Copilot Chat opens in **Work** mode, the response mode selector isn’t shown. In **Work** mode, Copilot is optimized for secure, work context queries, so it automatically manages response depth for you. When you switch to **Web** mode, the response mode selector appears, allowing you to choose between faster responses or deeper reasoning. Once the selector is enabled, it remains visible as you switch between **Work** and **Web** modes.

1. If you’ve used **Copilot in Excel**, you know that it also includes a response control selector. However, its options are different from the Chat selector. In Copilot Chat, the selector controls how deeply Copilot reasons about your request. In Excel, the selector controls which AI model performs the work. Although these selectors might look similar, they control different aspects of Copilot and aren't the same setting.

1. In the prompt field, click on **+ (1)** and then select **Attach cloud files (2)** that we should see the already files in the onedrive location. 

   ![](../media/Module3/E1T1S5.png)

1. The following documents emulate various emails, Teams messages, and documents across Boulder Innovations (BI) that reference the Network Modernization and Security Upgrade Project. On the Onedrive popup wizard, search with **BI (1)** and select each of the following docuemnts **(2)** then click on **Select (3)**:

    - **BI Project Proposal Draft.docx**
    - **BI Email Thread – Budget Discussion.docx**
    - **BI Teams Chat Export.txt**
    - **BI Meeting Notes – Stakeholder Brief.docx**
    - **BI Email – Vendor Quote Summary.docx**
    - **BI Security Risk Memo.docx**
   
      ![](../media/Module3/E1T1S6.png)

1. Then ask **Copilot** with the below prompt attached with the files to summarize all project requirements from those sources. It should identify key stakeholders and outline the project’s purpose, objectives, and expected deliverables. Have it Create a concise project framework summary that you can share with leadership. It should also map each section to its sources and review the results.

      ``` 
      Summarize Boulder Innovation’s ‘Network Modernization and Security Upgrade’ project using the attached documents. Create a concise framework for leadership that covers: purpose and scope, top objectives, key deliverables, milestones, risks, and stakeholders. Cite your sources (file names and dates) and note any conflicting details. Present the summary in short sections and bullet points, followed by an appendix that maps each section to its sources.
      ```

      > **NOTE:** For this first prompt, we’ve provided the text so you can see what an effective prompt looks like when it incorporates the four key elements discussed in the Introduction unit. You must write all remaining prompts in this exercise, but in doing so, you can use this prompt as a model to emulate.

      ![](../media/Module3/E1T1S7.png)

1. When you’re finished, ask Copilot with the below prompt.
      ```
      Turn the results into a formatted Word document that you can download and share with the CIO.
      ```
     ![](../media/Module3/E1T1S8.png)

1.  Scroll down to the response you will see **... (1)** click on it and then select **Export to Word (2)**. Wait until the draft is ready and click on **Open Word (3)** from the popup wizard.

      ![](../media/Module3/E1T1S9.png)

      ![](../media/Module3/E1T1S9i.png)

1. Open the file in Word and review it. Verify that it contains all the requested information.

1.  On the **Word** home page, click on **Copilot** which is in the bottom right corner.

      ![](../media/Module3/E1T1S11.png)

1. On the **Lets edit your document** Copilot Chat wizard, after reviewing the document, you feel that it could use some visuals to enhance a few of the sections. Then give the prompt to Copilot. 
      ```
      Suggest some images, charts, or SmartArt graphics that can enhance the content in the document.
      ```

      ![](../media/Module3/E1T1S12.png)

1. From the list of suggestions, select one that you would like Copilot to generate and ask it to generate that image.

      ```
      Generate a new image to Purpose and Scope section in the document.
      ```

      > **NOTE:** Due to time constraints and the time it takes Copilot to generate images, limit your request to one image.

1. Place your cursor in the document where you want Copilot to insert the image. Once Copilot generates the image in the Copilot pane, hover over the image and select the plus **(+)(1)** sign that appears. Doing so inserts the image **(2)** into the document at the location of your cursor. 

      ![](../media/Module3/E1T1S14.png)

      > **NOTE:** If you want to undo the changes, you can just hit on **Undo** whatever the changes Copilot have made it will be removed. Retry giving a different prompt to see how Copilot generates the results.

1. Finally, you feel that a Question and Answer (Q&A) section would be helpful for leadership. Place your cursor at the end of the document, which is where you want Copilot to insert the Q&A section. Then ask Copilot with the prompt.
      ```
      Add a Q&A section in the document that includes potential questions and answers based on the document content.
      ```
1. Review the Q&A section. To generate more thought-provoking questions and answers, enter the provided prompt in the **Copilot** prompt box.

      ```
      Generate a different set of questions and answers that provoke deeper thinking, challenge assumptions, and connect the project to broader business and industry contexts.
      ```

1. Review the enhanced Q&A section generated by Copilot.

1. Review the suggested prompts displayed in the **Copilot** pane. If any additional changes are required, select the appropriate prompt and submit the request; otherwise, select **Done**.

   ![](../media/Module3/E1T1S17.png)

1. You plan to use this document in Task 3 as the basis for an executive presentation, so make note of the file name in your OneDrive.

## Summary

In this task, you used Microsoft 365 Copilot Chat to analyze project documents, emails, meeting notes, and Teams discussions related to the Network Modernization and Security Upgrade Project. You created a structured project framework that outlined objectives, deliverables, stakeholders, milestones, and risks, and then exported the results to Word. You enhanced the document with visual content and a leadership-focused Q&A section, creating a comprehensive project briefing that can be used to support executive reviews and future planning activities.

## You have successfully completed the exercise. Click on Next >> to proceed with the next exercise.

![](../media/ms4004-next.png)