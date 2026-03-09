# CST8912-LiveChatApplication
Users (Browser / Mobile Web)
        |
        v
Azure Static Web Apps
        |
        +--> Azure Functions
        |       - login / negotiate
        |       - connect
        |       - message
        |       - history
        |       - rooms/presence/receipts
        |
        +--> Azure Web PubSub
        |       - WebSocket connections
        |       - groups/rooms
        |       - broadcasts
        |
        +--> Azure Cosmos DB
        |       - users
        |       - conversations
        |       - messages
        |       - receipts
        |
        +--> Azure Blob Storage
        |       - images
        |       - attachments
        |       - avatars
        |
        +--> Azure Key Vault
        |       - secrets/endpoints/keys
        |
        +--> Application Insights + Azure Monitor
