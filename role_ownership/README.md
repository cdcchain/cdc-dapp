## mining_pool_ownership
> mining pool ownership contract

- **online contract interface**

1. init_share(arg: string)
>
>  set holder's shares, can only call once <br/>
>  params: string <br/>
>  ex.: "name1, share1, name2, share2" <br/>
>

2. submit_share_proposal(arg: string)
>
> submit a proposal of changing holder shares
> params: string <br/>
> ex.: "name1, share1, name2, share2" <br/>
> 

3. get_share_percent_of_share_proposal(_: string)
>
> get the share percent to pass a share proposal
> params: just input empty string("") <br/>
>

4. set_share_percent_of_share_proposal(arg: string) 
>
> set the share percent to pass a share proposal(should in precision style)
> params: string <br/>
> ex.: "6000"(set 60% share percent to pass a share proposal)<br/>
>

5. agree_share_proposal(_: string)
>
> whether agree the change share proposal
> params: just input empty string("") <br/>
>

6. disagree_share_proposal(_: string)
>
> whether disagree the change share proposal
> params: just input empty string("") <br/>
>

7. submit_operator_proposal(arg: string)
>
> submit a proposal of changing contract operator
> params: string <br/>
> ex.: "name1" <br/>
> 

8. get_share_percent_of_operator_proposal(_: string)
>
> get the share percent to pass a operator proposal
> params: just input empty string("") <br/>
>

9. set_share_percent_of_operator_proposal(arg: string)
>
> set the share percent to pass a operator proposal(should in precision style)
> params: string <br/>
> ex.: "6000"(set 60% share percent to pass a share proposal)<br/>
>

10. agree_operator_proposal(_: string)
>
> whether agree the change operator proposal
> params: just input empty string("") <br/>
>

11. disagree_operator_proposal(_: string)
>
> whether disagree the change operator proposal
> params: just input empty string("") <br/>
>


- **offline contract interface**

1. get_pool_share_info(_: string)
>
> get pool share info
> params: just input empty string("") <br/>
>

2. get_contract_admin_info(_: string)
>
> get pool contract admin info
> params: just input empty string("") <br/>
>

3. get_contract_admin_on_chain(_: string)
>
> get pool contract admin info store in chain data
> params: just input empty string("") <br/>
>

4. get_contract_operator_info(_: string)
>
> get pool contract operator info
> params: just input empty string("") <br/>
>

5. get_contract_operator_on_chain(_: string)
>
> get pool contract operator info store in chain data
> params: just input empty string("") <br/>
>

6. get_share_proposal_state(_: string)
>
> get share proposal state 
> params: just input empty string("") <br/>
>

7. get_share_proposal_info(_: string)
>
> get share proposal info
> params: just input empty string("") <br/>
>

8. get_operator_proposal_state(_: string)
>
> get operator proposal state 
> params: just input empty string("") <br/>
>

9. get_operator_proposal_info(_: string)
>
> get operator proposal info
> params: just input empty string("") <br/>
>

