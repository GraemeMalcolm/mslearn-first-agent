---
lab:
  title: Publish and use your agent
  description: Publish your agent and use it in a client application.
  level: 200
  duration: 20 minutes
  islab: true
---

# Publish and use your agent

In the previous exercises, used Microsoft Foundry and Visual Studio code to develop a computing history agent.

Now you're ready to publish the agent to its own endpoint, and consume it in an application.

This exercise should take approximately **20** minutes to complete.

## Publish your agent

So far you've developed and tested your agent within a Foundry project. To take it into production, you need to publish it to a dedicated endpoint from which client applications can consume it.

1. In a web browser, open [Microsoft Foundry](https://ai.azure.com){:target="_blank"} at `https://ai.azure.com` and sign in using your Azure credentials.
1. Switch to the **New Foundry** view if necessary, and open the project in which you created the *computing-historian* agent.
1. Select the **Build** menu, and in the **Agents** page, select the **computing-historian** agent.
1. In the **Publish** drop-down list, select **Publish agent** and publish the latest version of your agent.
1. View the published agent details. In particular, note the **Responses API endpoint** that clients apps can use to connect to your agent.

    ![Screenshot of the agent publishing confirmation message.](./media/publish-agent.png)

1. Note that you can perform additional steps to publish your agent for integration with Teams and Microsoft 365 Copilot. However, in this exercise, select **Close**.

    > **Tip**: You can use the **View details** option in the **Publish** drop-down list to re-open the agent details.

