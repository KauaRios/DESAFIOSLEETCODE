Dada uma matriz inteira nums de comprimento n, você deseja criar uma matriz ans de comprimento 2n onde ans[i] == nums[i] e ans[i + n] == nums[i] para 0 <= i < n (0-indexado).

Especificamente, ans é o concatenação de dois nums matrizes.

Retornar a matriz ans.

 

Exemplo 1:

Entrada: números = [1,2,1]
Saída: [1,2,1,1,2,1]
Explicação: A matriz ans é formada da seguinte forma:
- ans = [nums[0],nums[1],nums[2],nums[0],nums[1],nums[2]]
- ans = [1,2,1,1,2,1]
Exemplo 2:

Entrada: nums = [1,3,2,1]
Saída: [1,3,2,1,1,3,2,1]
Explicação: A matriz ans é formada da seguinte forma:
- ans = [nums[0],nums[1],nums[2],nums[3],nums[0],nums[1],nums[2],nums[3]]
- ans = [1,3,2,1,1,3,2,1]
 

Restrições:

n == nums.length
1 <= n <= 1000
1 <= nums[i] <= 1000
