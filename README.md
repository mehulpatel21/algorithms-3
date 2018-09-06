# Algorithms in C and Python

## List of Algorithms

###### Level 1: Easy
###### Level 2: Medium
###### Level 3: Hard
###### Level 4: Memory based

#### **: If there multiple solutions for a given solution, go with this.

- [Rabin karp](rabin_karp.c): Hashing based substring matching algorithm.
- [Karatsuba algo](karatsuba.py): Efficient way to multiply 2 numbers, karatsuba algo.
- [Check prime](is_prime.go): Check if a number is prime or not.
- [Babylonian - Square root](babylonian_square_root.go): Babylonian method to find square root of a number.
- [BFS traversal](bfs.py): Creates a directed graph and performs BFS traversal.
- [DFS traversal](dfs.py): Creates a directed graph and performs DFS traversal.
- [Check cycle in graph](cycle_in_graph.py): Uses DFS approach to check if cycle exists in a directed graph.
- [Topological sort](topological_sort.py): Topological order of directed acyclic graph(DAG) using DFS.
- [Level order tree traversal](Level-3/level_order_tree_traversal.c): Level order traversal of a tree | O(n^2) | Level 3.
- [Level order tree traversal using queue**](Level-2/level_order_tree_traversal_using_queue.c): Level order traversal of a tree using queue | O(n) solution, requires extra space to manage queue | O(n) time and space | Level 2.
- [Shortest path of DAG](shortest_path_for_DAG.py): Find shortest in a directed acyclic graph from a source vertex to all reachable vertex | O(V + E).
- [Bellman ford](Level-3/bellman_ford.py): Bellman ford algo to find shortest path in a graph | O(VE) | Level 3.
- [Edit distance](Level-3/edit_distance.c): Find minimum operations required to convert a source string to target string | Level 3.
- [Flip your caps](Level-3/flip_your_cap.c): You all will conform | flip your cap(s) puzzle | Level 3.
- [Find 1-D peak](Level-2/find_peak_element.c): Find 1-D peak from an array | Level 2.
- [Find 2-D peak](Level-3/find_2d_peak.c): Find 2-D peak from a 2-D array | Level 3.
- [Find second largest number](Level-1/second_largest_in_array.c): Find second largest number from an array | Level 1.
- [Find element with rank k](Level-1/rank_k_element_in_2_sorted_array_O_k.c): Find element with rank k(or kth smallest number) between 2 sorted arrays in ascending sorted | O(n) | Level 1.
- [Find element with rank k - log(n)**](Level-3/rank_k_element_in_2_sorted_array_log_k.c): Find element with rank k(or kth smallest number) between 2 sorted arrays in ascending sorted having distinct elements | O(log(n)) | Level 3.
- [Search element in rotated sorted array](Level-3/search_in_rotated_sorted_array.c): Search an element from rotated sorted array | Level 3.
- [Heap sort using max heap](heap_sort_using_max_heap.c): Build a max heap and sort array in ascending order.
- [Heap sort using min heap](heap_sort_using_min_heap.c): Build a min heap and sort array in descending order.
- [Check strings has unique characters](Level-1/unique_characters_check_in_string.c): Check if a string has all unique characters or not | Level 1.
- [2 strings are permutations](Level-2/strings_permutation_check.c): Check if 2 strings are permutations of each other or not | Level 2.
- [Update input string](Level-2/url_formatter.c): Update(in-place) input string to have space replaced with %20 | O(n) | Level 2.
- [Is permutation palindrome](Level-2/is_any_permutation_palindrome.c): Check if any permutation of given string is palindrome or not | Level 2.
- [Check 2 strings, one edit away](Level-2/are_two_strings_one_edit_away.c): Check if 2 strings are max one edit away or not | O(n) | Level 2.
- [String compression](Level-2/string_compression.c): Compress string, show count for consecutive repeating characters | O(n) | Level 2.
- [Rotate square matrix](Level-3/rotate_matrix.c): Rotate square matrix clockwise by 90 degrees | O(n) | Level 3.
- [Clear row and column if 0 found](Level-3/clear_matrix_rows_and_coulmns.c): If an element in a matrix is 0, its entire row and column are set to 0 | O(MxN) | Level 3.
- [2 strings are rotations](Level-2/are_2_strings_rotations.c): Check if 2 strings are rotations of each other or not | O(n) | Level 2.
- [Longest increainng subsequence - O(n^2)](Level-3/LIS_O_n2.c): Find length of longest increasing subsequence from an unsorted array | O(n^2) | Level 3.
- [Longest increainng subsequence - O(nlogn)**](Level-3/LIS_O_nlogn.c): Find length of longest increasing subsequence from an unsorted array | O(nlogn) | Level 3.
- [Binary representation](Level-1/binary_representation.c): Print binary representation of an integer | Level 1.
- [Insert M into N](Level-2/insert_bits_from_M_into_N.c): Insert bits in M to N at positions between i and j | Level 2.
- [Decimal fraction to binary](Level-1/decimal_fraction_to_binary.c): Convert binary fraction number between 0 and 1 to binary representation | Level 1.
- [Flip a bit, get max sequence of 1s](Level-2/flip_a_bit_to_get_max_seq_of_ones.c): Flip a bit to get maximum sequence of 1s in sequence | O(b) | Level 2.
- [Next largest number, same set bits](Level-4/next_largest_same_num_of_bits_set.c): Given a positive integer, find next largest number having same number of set bits | O(b) | Level 4.
- [Previous number, same set bits](Level-4/previous_num_having_same_num_of_bits_set.c): Given a positive integer, find previous number having same number of set bits | O(b) | Level 4.
- [Bit flips required to convert](Level-2/bits_flipped_to_convert.c): Determine the number of bits need to flip to convert integer A to B | Level 2.
- [Swap odd and even bits](Level-2/swap_odd_even_bits.c): Program to swap odd and even bits in an integer | Level 2.
- [Update screen array, draw line](Level-3/draw_line.c): Update pixels array based on input pixel points to draw a line | Level 3.
- [Knapsack problem](Level-4/knapsack.c): Given a knapsack (bag with capacity W), and N items having weights and values, Select items such that value is maximized | O(nxW) | Level 4.
- [Knapsack problem - Maximize weight](Level-4/knapsack_maximize_weight.c): Given a knapsack, maximize weights that can be carried in given knapsack, No item values given | O(nxW) | Level 4.
- [Merge 2 sorted arrays, in place](Level-2/merge_2_sorted_arrays_in_place.c): Merge 2 sorted arrays, in place | O(A + B) | Level 2.
- [Groups anagrams](Level-2/group_anagrams.py): Write a method to sort an array of strings so that all the anagrams are next to each other. | O(MxNxlog(N)) | Level 2.
- [Sorted search, no size](Level-1/search_in_infinite_sorted_array.c): Search an element from an infinite sized (size of array not given) sorted array | O(log(p)) | Level 1.
- [Search in sparse array](Level-2/search_string_in_sparse_array.py): Search a string from sparsely populated array of strings (other places has empty string) | O(log(n)) | Level 2.
- [Find all duplicates in array](Level-2/find_duplicates_in_4k_space.c): Find all duplicates in array (range 1 to 32,000) with memory 4k | O(n) | Level 2.
- [Search in sorted matrix](Level-3/sorted_matrix_search.c): Search for an element in a matrix having each row and each column sorted | O(M + N) | Level 3.
- [Remove obstacle](Level-2/remove_obstacle.py): Remove obstacle, amazon online test | O(MxN) | Level 2.
- [Rank from stream](Level-3/rank_from_stream.c): Find rank of an element from a stream of data | O(logn) | Level 3.
- [Peaks and valleys, sorting method](Level-2/peaks_and_valleys_O_nlogn.py): Arrange an unsorted in alternating sequence of peaks and valleys | O(NlogN) | Level 2.
- [Peak and valley, O(n) method**](Level-3/peaks_and_valleys_O_n.py): Arrange an unsorted array in alternating sequence of peaks and valleys | O(n) | Level 3.
- [Count ways to run n steps](Level-2/count_steps.py): Count the number of ways possible to run stairs having n steps (can take 1, 2 or 3 steps) | O(n) | Level 2.
- [Path of robot in grid](Level-3/robot_in_a_grid.py): Find path traversed by robot to reach from 0, 0 to row - 1, col - 1 | O(rc) | Level 3.
- [Min from sorted rotated](Level-3/min_in_sorted_rotated_array.c): Find min element from sorted rotated array | O(log(n)) | Level 3.
- [Tree level with max width](Level-3/level_with_max_width.c): Find tree level having max width/nodes | O(n) | Level 3.
- [Find magic index](Level-2/magic_index.c): Find magic index from an sorted array having distinct elements | O(log(n)) | Level 2.
- [Find magic index, duplicates allowed**](Level-3/magic_index_with_duplicates.c): Find magic index from an sorted array (having duplicates) | O(log(n)) | Level 3.
- [Generate all subsets of a set](Level-3/generate_all_subsets.py): Generate all subsets of a given set | O(n2^n) | Level 3.
- [Generate all subsets, binary method**](Level-2/generate_all_subsets_binary_method.py): Generate all subsets of a given set, binary representation method | O(n2^n) | Level 2.
- [Multiply 2 integers](Level-3/multiply_integers.c): Multiply 2 positive integers without using multiply operator | O(log(s)) | Level 3.
- [Print fibonacci numbers](Level-1/fibonacci.c): Print first n fibonacci numbers | O(n) | Level 1.
- [Tower of hanoi](Level-3/tower_of_hanoi.c): Print steps to solve tower of hanoi problem for n disks | O(2^n) | Level 3.
- [Compute all permutations - Unique chars**](Level-4/compute_all_permutations_unique_chars.py): Compute all permutations of a given string having unique characters | O(n^2 * n!) | Level 4.
- [Compute all permutations - Repeated chars](Level-4/compute_all_permutations_non_unique_chars.py.py): Compute all permutations of a given string having repeated characters | O(n * n!) | Level 4+.
- [Pair of valid parens](Level-2/pair_of_parens.py): Print all valid combinations of n pairs of parentheses | O(n * n!) | Level 2.
- [Paint fill](Level-2/paint_fill.py): Fill surrounding area with new color | O(2^r * 2^c) | Level 2.
- [Ways to represent n cents](Level-4/ways_to_represent_n_cents.c): Find number of ways to represent n cents using quarters, dimens, nickels and pennies | O(n * NUM_OF_DENOMS) | Level 4.
- [Place 8 queens on 8x8](Level-4/place_eight_queens.py): Print all ways to arrange 8 queens on a 8x8 chessboard so that none attack any other | O(GRID_SIZE^3) | Level 4.
- [Stack boxes to maximize height](Level-4/stack_boxes.py): Stack boxes to to have maximum height | O(2^n) | Level 4.
- [Boolean evaluation ways](Level-3/boolean_evaluation_ways.py): Total number of ways to get expected boolean result from a boolean expression | O(n) | Level 3.
- [Print prime numbers](Level-3/print_all_prime_numbers.py): Print all prime numbers from 1 to n, sieve of eratosthenes method | O(sqrt(n)log(log(n))) | Level 3.
- [Quick sort](Level-4/quick_sort.c): Implement quick sort for array of random numbers | O(nlogn) | Level 4.
- [Find min range, k sorted arrays](Level-3/min_range_k_sorted_arrays.c): Find min range which will have elements from all k arrays | O(n*k) | Level 3.
- [Shortest winter days](Level-3/shortest_winter_days.c): Find shortest winter days from temperatures given in an array | O(n) | Level 3.
- [Min positive integer missing](Level-2/smallest_positive_missing.py): Find minimum positive number from an array having random integers | O(n) | Level 2.
- [Season with max amplitude](Level-2/season_with_max_amplitude.py): Find season with max amplitude | O(n) | Level 2.
- [Create sequence of 'a' and 'b'](Level-3/three_non_consecutive_ab.py): Given 2 numbers A and B, create sequence with at max 2 consecutive 'a' and 'b | O(A + B) | Level 3.
- [Check strings same](Level-1/case_insensitive_strcmp.c): Write a function to check if 2 strings are same, ingoring case | Level 1.
- [Multiple of 4](Level-1/check_multiple_of_4.c): Check if a number of 4 or not | Level 1.
- [Find 7n/8](Level-1/find_7by8_of_n.c): Find 7n/8 without using * and / operators | Level 1.
- [Clear both elements](Level-1/unset_both.c): Clear both array elements having atleast a 0 and 1 | Level 1.
- [Binary palindrom](Level-2/is_num_binary_palindrdom.c): Check if a numbers binary representation is palidrom or not | Level 1.
- [Product of elements](Level-2/product_array_elements_except_self.c): Create a array having product of all elements except element at self index | Level 2.
- [Modified fibonacci](Level-1/modified_fibonacci.py): ######### File header pending ############# | Level 1.
- [Next word in dictionary](Level-2/next_word_in_dictionary.py): ########### FIle header pending ########## | Level 2.
