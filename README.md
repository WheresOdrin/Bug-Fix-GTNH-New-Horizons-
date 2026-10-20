# Bug-Fix-GTNH-New-Horizons-
When updating GTNH from instance 2.9-1 to 2.9-2. Coins were able to be put into a team wallet and personal wallet, in a singleplayer world coins located in a team wallet instead of personal wallet do not get transfered over correctly, as the team wallet button is no longer accessible in singleplayer worlds as of the 2.9-2 update.
The player will then not be able to see or use any of their coins inside the gui of the vending machine. This only affects players that update their game on daily builds of the modpack and not full releases.
Removed the Team coin file, as it should not be included when loading a singleplayer world
Adding coins via commands in game where not showing up, and trying to disband a team is not allowed in singleplayer


Here is the original file located in my instance.
{
  "Members": [
    "3ac4fac8-ef47-4c0d-b374-96f17a291206"
  ],
  "Officers": [
    "3ac4fac8-ef47-4c0d-b374-96f17a291206"
  ],
  "Owners": [
    "3ac4fac8-ef47-4c0d-b374-96f17a291206"
  ],
  "TeamData": {
    "VM": {
      "players": [
        {
          "uuid": "3ac4fac8-ef47-4c0d-b374-96f17a291206",
          "wallet": {}
        }
      ],
      "tradeHistory": [
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791823044414L",
          "notificationQueued": "0B",
          "tradeCount": 3,
          "uuid": "08702d0a-20ae-43d8-97ca-767f46ee7d77"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1790308330393L",
          "notificationQueued": "0B",
          "tradeCount": 2,
          "uuid": "4548bac9-6eff-430e-8bb8-c3d47f5a3367"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791835302530L",
          "notificationQueued": "0B",
          "tradeCount": 4,
          "uuid": "1a60d65d-675f-484a-a1cd-0ddac54187bf"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791832881530L",
          "notificationQueued": "0B",
          "tradeCount": 3,
          "uuid": "67be02fc-43a0-4abb-926e-29f7b5511515"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791839024332L",
          "notificationQueued": "0B",
          "tradeCount": 6,
          "uuid": "d59b3bee-192d-451e-942e-51779a075ebd"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791828034179L",
          "notificationQueued": "0B",
          "tradeCount": 2,
          "uuid": "b49da4ec-7db1-4b6b-940c-aa5002f169ec"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791849658131L",
          "notificationQueued": "0B",
          "tradeCount": 25,
          "uuid": "1d3ac49e-9cdc-4ad7-84c9-a7a8d7123fb0"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791849657480L",
          "notificationQueued": "0B",
          "tradeCount": 25,
          "uuid": "908b32c9-2bc4-424c-80f2-fcfa0cce6421"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791849657979L",
          "notificationQueued": "0B",
          "tradeCount": 8,
          "uuid": "691e5d0c-cd5e-408f-8970-c0bc6a6527c4"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791827588930L",
          "notificationQueued": "0B",
          "tradeCount": 3,
          "uuid": "809e5f9b-a30a-47f2-8c83-a82c93d55ac9"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1790313771440L",
          "notificationQueued": "0B",
          "tradeCount": 5,
          "uuid": "d3833aa2-61ab-4010-8e55-1f184c9115c9"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791827589429L",
          "notificationQueued": "0B",
          "tradeCount": 3,
          "uuid": "67d5ae34-d147-435b-8c83-3eec0086bdc5"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791835305330L",
          "notificationQueued": "0B",
          "tradeCount": 4,
          "uuid": "bd9dc86d-1b76-44ec-bbc2-25b41b6ae9a4"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791849657629L",
          "notificationQueued": "0B",
          "tradeCount": 8,
          "uuid": "a4841687-63ba-4446-a757-9539cad3d556"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791758730749L",
          "notificationQueued": "0B",
          "tradeCount": 2,
          "uuid": "4c727a19-aa35-4b7d-93cb-d8d181b0335c"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791819505924L",
          "notificationQueued": "0B",
          "tradeCount": 1,
          "uuid": "66f71bc0-72c0-4608-b7c4-f27447155d0c"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791758727985L",
          "notificationQueued": "0B",
          "tradeCount": 1,
          "uuid": "37ae2964-efda-4dfd-8f7a-7b5419be938a"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1790306331847L",
          "notificationQueued": "0B",
          "tradeCount": 4,
          "uuid": "30b41368-dbde-4fd5-a734-c23abbd23893"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1790318144340L",
          "notificationQueued": "0B",
          "tradeCount": 2,
          "uuid": "8db4ef69-2921-4d94-b459-6ecda3720f57"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791832882378L",
          "notificationQueued": "0B",
          "tradeCount": 19,
          "uuid": "f0398e09-498c-40d2-8f01-3b4db14e98f6"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1790305004105L",
          "notificationQueued": "0B",
          "tradeCount": 1,
          "uuid": "5e70b21b-94b5-4146-b128-cb7ecaa46eb0"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791835303780L",
          "notificationQueued": "0B",
          "tradeCount": 3,
          "uuid": "1f0434b2-f7d1-4130-ad03-9a5118953eec"
        },
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791819505623L",
          "notificationQueued": "0B",
          "tradeCount": 1,
          "uuid": "0ea1ce5e-218e-4ee5-9c62-ff32963b57a1"
        }
      ],
      "wallet": {
        "currency": [
          {
            "amount": 1004,
            "currency": "adventure"
          },
          {
            "amount": 15,
            "currency": "bees"
          },
          {
            "amount": 735,
            "currency": "chemist"
          },
          {
            "amount": 140,
            "currency": "cook"
          },
          {
            "amount": 1630,
            "currency": "darkWizard"
          },
          {
            "amount": 383,
            "currency": "farmer"
          },
          {
            "amount": 87,
            "currency": "forestry"
          },
          {
            "amount": 25,
            "currency": "smith"
          },
          {
            "amount": 1560,
            "currency": "survivor"
          },
          {
            "amount": 624,
            "currency": "technician"
          }
        ]
      }
    },
    "visualprospecting": {}
  },
  "TeamName": "USERNAME",
  "UUID": "2361011b-f58a-4621-a587-b03cc63508c1",
  "Version": 1
}



Here is the file that should have be implemented in when transfering over files to a new instance




{
  "Members": [
    "3ac4fac8-ef47-4c0d-b374-96f17a291206"
  ],
  "Officers": [
    "3ac4fac8-ef47-4c0d-b374-96f17a291206"
  ],
  "Owners": [
    "3ac4fac8-ef47-4c0d-b374-96f17a291206"
  ],
  "TeamData": {
    "VM": {
      "players": [
        {
          "uuid": "3ac4fac8-ef47-4c0d-b374-96f17a291206",
          "wallet": {
            "currency": [
              {
                "amount": 1004,
                "currency": "adventure"
              },
              {
                "amount": 735,
                "currency": "chemist"
              },
              {
                "amount": 140,
                "currency": "cook"
              },
              {
                "amount": 1630,
                "currency": "darkWizard"
              },
              {
                "amount": 383,
                "currency": "farmer"
              },
              {
                "amount": 87,
                "currency": "forestry"
              },
			  {
                "amount": 15,
                "currency": "bees"
              },
              {
                "amount": 25,
                "currency": "smith"
              },
              {
                "amount": 1560,
                "currency": "survivor"
              },
              {
                "amount": 624,
                "currency": "technician"
              }
            ]
          }
        }
      ],
      "tradeHistory": [
        {
          "cooldownTradeCount": 1,
          "lastTrade": "1791605249548L",
          "notificationQueued": "0B",
          "tradeCount": 1,
          "uuid": "4548bac9-6eff-430e-8bb8-c3d47f5a3367"
        }
      ],
      "wallet": {}
    },
    "gt.powerfails": {
      "blob": ""
    },
    "visualprospecting": {}
  },
  "TeamName": "USERNAME",
  "UUID": "2361011b-f58a-4621-a587-b03cc63508c1",
  "Version": 1
}
