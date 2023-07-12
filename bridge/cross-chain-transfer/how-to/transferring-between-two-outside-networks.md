# 두 외부 네트워크로 사이의 전송

### 지갑연결

시작하려면 선택한 네트워크와 상호작용하고 커미션을 지불하는 데 각각 사용될 옥터스 브리지 인터페이스에 우선 지갑을 연결해야 합니다.

**지갑연결(Connect Wallet)**을 클릭하시고 [두 지갑을 모두 연결하세요.](../../../getting-started/how-to-connect-wallets.md#connect-wallets)

### 소스(출발 네트워크)와 목적지 블록체인 선택

시작하려면 **크로스체인 전송(Cross-Chain Transfer)** 페이지로 가서 상단의 **브리지(Bridge)** 버튼을 누르십시오.&#x20;

여기서 토큰 전송을 위한 소스(출발지점, Source)와 목적지(Destination) 네트워크를 선택할 수 있습니다.

"<mark style="color:orange;">**From**</mark>" 은 여러분께서 토큰을 인출하실 네트워크를 의미하며 "<mark style="color:orange;">**To**</mark>"는 토큰이 보내질 목적지를 뜻합니다.&#x20;

<mark style="color:green;">**수신자의 지갑주소**</mark>를 수동으로 입력하는 것도 가능합니다. 그렇지만 가스 수수료는 연결된 지갑에서 차감됩니다.

![](<../../../.gitbook/assets/image (36).png>)

### Select token and amount



**다음(Next)**을 클릭하고 **토큰 및 액수 선택 페이지(Select token and amount)**로 갑니다.

여기서는 다른 네트워크로로 전송(송금)할 토큰을 선택하게 되며 전송할 토큰의 액수도 입력하게 됩니다. \
You can see a list of all tokens available for sending on the corresponding page.

{% content-ref url="../../concepts/available-chains-and-assets.md" %}
[available-chains-and-assets.md](../../concepts/available-chains-and-assets.md)
{% endcontent-ref %}

Review the number of tokens that you will receive as a result of the operation and click **Next**.

![](<../../../.gitbook/assets/image (51).png>)

### Permission to use tokens

At this step, you need to grant Octus Bridge permission to use tokens from the balance of your address. There are two types of permission:

1. You can confirm an infinite amount so that you do not have to pay for confirmation later if you decide to make another transfer.
2. You can choose to only confirm the amount required for this transfer.

**Regardless of your choice, the bridge will only use the amount you ask for.**

After choosing one of the options, click **Confirm** and confirm the action in your wallet (the window should open automatically).\
Then you can proceed to the next step.

![](<../../../.gitbook/assets/image (45).png>)

### Transfer status

The **Transfer status** page displays the steps in the transfer process.\
At this step, the tokens are directly sent to the selected network.\
Basically all you have to do is wait. The whole process happens automatically, you only need to make a few clicks on the site itself and inside the wallet to confirm the operation and pay commissions.\
Octus Bridge will keep you informed every step of the transaction so you don't have to worry about getting your funds.

{% hint style="warning" %}
**Please note that all subsequent actions are irreversible!** Tokens will be debited from your wallet and will not be available until you complete the transfer.
{% endhint %}

First, click on **Transfer** to send your tokens to the source network storage.\
Confirm this action in your wallet and wait for a while for the action to complete.

![](<../../../.gitbook/assets/image (1).png>)

After a while, you will see that the status of this action has changed to **Confirmed**.\
Now you need to prepare tokens for sending to the Everscale network.\
Click **Prepare** and confirm the action in the wallet.

Wait until all statuses change to **Confirmed** - it won't take long.

There will be a notification that the Metamask network is not configured properly, this is not a problem, click **Edit Network** tab, this will take you to a screen that will allow you to change the network in the Metamask.

![](<../../../.gitbook/assets/image (37).png>)

After successfully completing all the steps, a window will open informing you that the transfer was completed successfully and the corresponding tokens will be added to your balance.
