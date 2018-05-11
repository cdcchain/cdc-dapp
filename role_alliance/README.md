## arbitrator_committee
> arbitrator committee contract

- **online contract interface**

1. init_chair(chair_man: string)
>
>  set arbitrator committee chair, can only call once <br/>
>  params: string <br/>
>  ex.: "name1" <br/>
>


2. submit_proposal(name: string)
>
>  submit a proposal of changing chair man <br/>
>  params: string <br/>
>  ex.: "name1" <br/>
>

3. get_percent_of_proposal(_: string)
>
> get the share percent to pass a change chair man proposal <br/>
> params: just input empty string("") <br/>
>

4. set_percent_of_proposal(arg: string)
>
> set the share percent to pass a change chair man proposal(should in precision style) <br/>
> params: string <br/>
> ex.: "6000"(set 60% share percent to pass a share proposal)<br/>
>

5. agree_proposal(_: string)
>
> whether agree the change chair man proposal <br/>
> params: just input empty string("") <br/>
>

6. agree_apply(arg: string)
>
> whether agree committee member apply <br/>
> params: string <br/>
> ex.: "contract_id, name1" <br/>
>

7. withdraw_from_contract(amount: string)
>
> withdraw from contract balance <br/>
> params: string <br/>
> ex.: "100"(should not multiply the precision)
>


- **offline contract interface**

1. get_chair_man(_: string)
>
> get chair man info <br/>
> params: just input empty string("") <br/>
>

2. get_proposal_state(_: string)
>
> get change chair man proposal state <br/>
> params: just input empty string("") <br/>
>

3. get_proposal_info(_: string)
>
> get change chair man proposal info <br/>
> params: just input empty string("") <br/>
>

4. get_committee_member(_: string)
>
> get committee member info <br/>
> params: just input empty string("") <br/>
>


## mining_pool_alliance
> mining pool alliance contract

- **online contract interface**

1. init_share(arg: string)
>
>  set holder's shares, can only call once <br/>
>  params: string <br/>
>  ex.: "name1, share1, name2, share2" <br/>
>

2. submit_share_proposal(arg: string)
>
> submit a proposal of changing holder shares <br/>
> params: string <br/>
> ex.: "name1, share1, name2, share2" <br/>
> 

3. get_share_percent_of_share_proposal(_: string)
>
> get the share percent to pass a share proposal <br/>
> params: just input empty string("") <br/>
>

4. set_share_percent_of_share_proposal(arg: string) 
>
> set the share percent to pass a share proposal(should in precision style) <br/>
> params: string <br/>
> ex.: "6000"(set 60% share percent to pass a share proposal)<br/>
>

5. agree_share_proposal(_: string)
>
> whether agree the change share proposal <br/>
> params: just input empty string("") <br/>
>

6. disagree_share_proposal(_: string)
>
> whether disagree the change share proposal <br/>
> params: just input empty string("") <br/>
>

7. submit_operator_proposal(arg: string)
>
> submit a proposal of changing contract operator <br/>
> params: string <br/>
> ex.: "name1" <br/>
> 

8. get_share_percent_of_operator_proposal(_: string)
>
> get the share percent to pass a operator proposal <br/>
> params: just input empty string("") <br/>
>

9. set_share_percent_of_operator_proposal(arg: string)
>
> set the share percent to pass a operator proposal(should in precision style) <br/>
> params: string <br/>
> ex.: "6000"(set 60% share percent to pass a share proposal)<br/>
>

10. agree_operator_proposal(_: string)
>
> whether agree the change operator proposal <br/>
> params: just input empty string("") <br/>
>

11. disagree_operator_proposal(_: string)
>
> whether disagree the change operator proposal <br/>
> params: just input empty string("") <br/>
>

12. agree_apply(arg: string)
>
> whether agree pool member apply <br/>
> params: string <br/>
> ex.: "contract_id, name1" <br/>
>

13. agree_arbitrator(arg: string)
>
> whether agree arbitrator apply <br/>
> params: string <br/>
> ex.: "contract_id, name1, amount" <br/>
>

14. pay_arbitrator(contract_id: string)
>
> pay arbitrator <br/>
> params: string <br/>
> ex.: "contract_id" <br/>
>


15. withdraw_from_contract(amount: string)
>
> withdraw from contract balance <br/>
> params: string <br/>
> ex.: "100"(should not multiply the precision)
>

- **offline contract interface**

1. get_pool_share_info(_: string)
>
> get pool share info <br/>
> params: just input empty string("") <br/>
>

2. get_contract_admin_info(_: string)
>
> get pool contract admin info <br/>
> params: just input empty string("") <br/>
>

3. get_contract_admin_on_chain(_: string)
>
> get pool contract admin info store in chain data <br/>
> params: just input empty string("") <br/>
>

4. get_contract_operator_info(_: string)
>
> get pool contract operator info <br/>
> params: just input empty string("") <br/>
>

5. get_contract_operator_on_chain(_: string)
>
> get pool contract operator info store in chain data <br/>
> params: just input empty string("") <br/>
>

6. get_share_proposal_state(_: string)
>
> get share proposal state <br/>
> params: just input empty string("") <br/>
>

7. get_share_proposal_info(_: string)
>
> get share proposal info <br/>
> params: just input empty string("") <br/>
>

8. get_operator_proposal_state(_: string)
>
> get operator proposal state <br/>
> params: just input empty string("") <br/>
>

9. get_operator_proposal_info(_: string)
>
> get operator proposal info <br/>
> params: just input empty string("") <br/>
>

10. get_alliance_member(_: string)
>
> get pool alliance member info <br/>
> params: just input empty string("") <br/>
>

11. get_arbitrator_info(_: string)
>
> get ppol arbitrator info <br/>
> params: just input empty string("") <br/>
>

## other alliance contracts' interface just reference above

