



 ______     ______   __  __     ______     __   __     ______    
/\  __ \   /\__  _\ /\ \_\ \   /\  ___\   /\ "-.\ \   /\  __ \   
\ \  __ \  \/_/\ \/ \ \  __ \  \ \  __\   \ \ \-.  \  \ \  __ \  
 \ \_\ \_\    \ \_\  \ \_\ \_\  \ \_____\  \ \_\\"\_\  \ \_\ \_\ 
  \/_/\/_/     \/_/   \/_/\/_/   \/_____/   \/_/ \/_/   \/_/\/_/ 
                                 

                     ethereum private network        

+================================================================+

						www.blockarray.com

#Network Status: DOWN - 11/26/2017 @ 4:14pm (UTC)
	?Reason: Reconfig Gensis Block Settings for new testnet <athenadmin>

#TestNet Registration Status: CLOSED
	?Reason: testnet brought down

#Comments: *

+================================================================+
#Azure Information
Subsription: Blockchain NonProd
Resource Group: bcdemo-leader
Location: East US

Resource prefix: leader
VM username: athenadmin
Password:

Network Size and Performance
Consortium MemberID: 0
Number of mining nodes per Member: 5
Mining Node storage performance: standard
Mining node storage replication: LRS
Mining node VM size: standard D1 v2
Number of load balanced tx: 2
Tx node storage performance: Standard
Tx node storage replication: LRS

Ethereum Settings
NetworkID: 13333337
Custom Genesis Block: No
Eth account password: #
Eth private key passphrase: #


+================================================================+

Accessing the Athena-TestNet with your ARY Token registration using MetaMask

You will need to change this to connect to the deployed private consortium network,
specifically to the load balancer in front of the transaction nodes. From the template output, retrieve the
exposed Ethereum RPC endpoint at port 8545, the second template output, and enter it in custom RPC as
shown below

RPC Athena-TestNet
	{athena-testnet:azure}

Registration Page for ARY Token to have Ether deposited into their private eth accounts
	{athena:array.network}
	
	This will transfer an allocation of ether to their new account







+================================================================+

#Ethereum Settings

Ethereum Network ID
	NetworkID for consortium ethereum network being deployed
	Allowed values: 5-999,999,999
	Default Value: 10101010 
		Use values above this to avoid collisions

+================================================================+

\End


			Copyright BlockArray Inc. 2017 All Rights Reserved.

				          www.blockarray.com
						contact@blockarray.com

