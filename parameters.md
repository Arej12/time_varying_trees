### Time-varying parameters Parameters:

- Lambda1 (birth rate1): U(0.01, 1.0)
- Mu/Lambda ratio: U(0.0, 0.9)
- Lambda2 (birth rate2): U(0.01,1.0) 
- t_1 (rate shift time): U(4,8)
- Target trees: 10000
- Max Time: U(6,15)
- Acceptance Criteria:
<ol type="a">
  <li>n_tips ∈ [100, 1000]</li>
  <li>tree.age(height)>t_1+2</li>
  <li>la1 / la2 > 1.1 or la1 / la2 < 0.9 OR mu_over_la1 / mu_over_la2 > 1.1 or mu_over_la1 / mu_over_la2 < 0.9</li>
  <li>n_tips before t_1>=20</li>
  <li></li>
</ol>
  
