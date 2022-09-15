# prove that cross ratio of four points is invariant under projectile transformation of the points

## projectile transformation of a point

$$ M(x) = \frac{ax + b}{cx + d} = \frac{N(x)}{D(x)}$$
we can write M as the 

## Cross ratio of four points on a line

$$C(x_1, x_2, x_3, x_4) = \frac{(x_1 - x_2)/(x_3 - x_2)}{(x_1 - x_4)/(x_3 - x_4)}$$
$$ = \frac{(x_1 - x_2)}{(x_1 - x_4)} \times \frac{(x_3 - x_4)}{(x_3 - x_2)}$$

we want to prove that: 

$$C(M(x_1), M(x_2), M(x_3), M(x_4))=C(x_1, x_2, x_3, x_4)$$

by substitution and writing $N_1 = N(x_1) and D_1 = D(x_1)$, etc., we have 
$$C(M(x_1), M(x_2), M(x_3), M(x_4))=\frac{\frac{N_1}{D_1} - \frac{N_2}{D_2}}{\frac{N_1}{D_1} - \frac{N_4}{D_4}} \times \frac{\frac{N_3}{D_3} - \frac{N_4}{D_4}}{\frac{N_3}{D_3} - \frac{N_2}{D_2}}$$

by algebraic simplification we have: 
$$ = \frac{(N_1 D_2 - N_2 D_1)}{(N_1 D_4 - N_4 D_1)} \times \frac{(N_3 D_4 - N_4 D_3)}{(N_3 D_2 - N_2 D_3)}$$

we can easily prove that 

$$ N_iD_j - N_jDi = (ad - bc)(x_i - x_j)$$
by substitution and simplification we prove the statement.
