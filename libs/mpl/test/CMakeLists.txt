include(BCMTest)

find_package(boost_bind)

bcm_test_link_libraries(boost_mpl
boost::bind
)


bcm_test(NAME mpl_aux__increased_arity SOURCES aux_/increased_arity.cpp COMPILE_ONLY)
bcm_test(NAME mpl_aux__largest_int SOURCES aux_/largest_int.cpp COMPILE_ONLY)
bcm_test(NAME mpl_aux__msvc_is_class SOURCES aux_/msvc_is_class.cpp COMPILE_ONLY)
bcm_test(NAME mpl_aux__template_arity SOURCES aux_/template_arity.cpp COMPILE_ONLY)
bcm_test(NAME mpl_aux__preprocessor_is_seq SOURCES aux_/preprocessor/is_seq.cpp COMPILE_ONLY)
bcm_test(NAME mpl_aux__preprocessor_token_equal SOURCES aux_/preprocessor/token_equal.cpp COMPILE_ONLY)

bcm_test(NAME mpl_advance SOURCES advance.cpp COMPILE_ONLY)
bcm_test(NAME mpl_always SOURCES always.cpp COMPILE_ONLY)
bcm_test(NAME mpl_apply SOURCES apply.cpp COMPILE_ONLY)
bcm_test(NAME mpl_apply_wrap SOURCES apply_wrap.cpp COMPILE_ONLY)
bcm_test(NAME mpl_arithmetic SOURCES arithmetic.cpp COMPILE_ONLY)
bcm_test(NAME mpl_as_sequence SOURCES as_sequence.cpp COMPILE_ONLY)
bcm_test(NAME mpl_assert SOURCES assert.cpp COMPILE_ONLY)
bcm_test(NAME mpl_at SOURCES at.cpp COMPILE_ONLY)
bcm_test(NAME mpl_back SOURCES back.cpp COMPILE_ONLY)
bcm_test(NAME mpl_bind SOURCES bind.cpp COMPILE_ONLY)
bcm_test(NAME mpl_bitwise SOURCES bitwise.cpp COMPILE_ONLY)
bcm_test(NAME mpl_bool SOURCES bool.cpp)
bcm_test(NAME mpl_comparison SOURCES comparison.cpp COMPILE_ONLY)
bcm_test(NAME mpl_contains SOURCES contains.cpp COMPILE_ONLY)
bcm_test(NAME mpl_copy SOURCES copy.cpp COMPILE_ONLY)
bcm_test(NAME mpl_copy_if SOURCES copy_if.cpp COMPILE_ONLY)
bcm_test(NAME mpl_count SOURCES count.cpp COMPILE_ONLY)
bcm_test(NAME mpl_count_if SOURCES count_if.cpp COMPILE_ONLY)
bcm_test(NAME mpl_deque SOURCES deque.cpp COMPILE_ONLY)
bcm_test(NAME mpl_distance SOURCES distance.cpp COMPILE_ONLY)
bcm_test(NAME mpl_empty SOURCES empty.cpp COMPILE_ONLY)
bcm_test(NAME mpl_equal SOURCES equal.cpp COMPILE_ONLY)
bcm_test(NAME mpl_erase SOURCES erase.cpp COMPILE_ONLY)
bcm_test(NAME mpl_erase_range SOURCES erase_range.cpp COMPILE_ONLY)
bcm_test(NAME mpl_eval_if SOURCES eval_if.cpp COMPILE_ONLY)
bcm_test(NAME mpl_filter_view SOURCES filter_view.cpp COMPILE_ONLY)
bcm_test(NAME mpl_find SOURCES find.cpp COMPILE_ONLY)
bcm_test(NAME mpl_find_if SOURCES find_if.cpp COMPILE_ONLY)
bcm_test(NAME mpl_fold SOURCES fold.cpp COMPILE_ONLY)
bcm_test(NAME mpl_for_each SOURCES for_each.cpp)
bcm_test(NAME mpl_front SOURCES front.cpp COMPILE_ONLY)
bcm_test(NAME mpl_has_xxx SOURCES has_xxx.cpp COMPILE_ONLY)
bcm_test(NAME mpl_identity SOURCES identity.cpp COMPILE_ONLY)
bcm_test(NAME mpl_if SOURCES if.cpp COMPILE_ONLY)
bcm_test(NAME mpl_index_of SOURCES index_of.cpp COMPILE_ONLY)
bcm_test(NAME mpl_inherit SOURCES inherit.cpp COMPILE_ONLY)
bcm_test(NAME mpl_insert SOURCES insert.cpp COMPILE_ONLY)
bcm_test(NAME mpl_insert_range SOURCES insert_range.cpp COMPILE_ONLY)
bcm_test(NAME mpl_int SOURCES int.cpp)
bcm_test(NAME mpl_char SOURCES char.cpp)
bcm_test(NAME mpl_integral_c SOURCES integral_c.cpp)
bcm_test(NAME mpl_is_placeholder SOURCES is_placeholder.cpp COMPILE_ONLY)
bcm_test(NAME mpl_is_sequence SOURCES is_sequence.cpp COMPILE_ONLY)
bcm_test(NAME mpl_iterator_tags SOURCES iterator_tags.cpp COMPILE_ONLY)
bcm_test(NAME mpl_joint_view SOURCES joint_view.cpp COMPILE_ONLY)
bcm_test(NAME mpl_lambda SOURCES lambda.cpp COMPILE_ONLY)
bcm_test(NAME mpl_lambda_args SOURCES lambda_args.cpp COMPILE_ONLY)
bcm_test(NAME mpl_list SOURCES list.cpp COMPILE_ONLY)
bcm_test(NAME mpl_list_c SOURCES list_c.cpp COMPILE_ONLY)
bcm_test(NAME mpl_logical SOURCES logical.cpp COMPILE_ONLY)
bcm_test(NAME mpl_lower_bound SOURCES lower_bound.cpp COMPILE_ONLY)
bcm_test(NAME mpl_map SOURCES map.cpp COMPILE_ONLY)
bcm_test(NAME mpl_max_element SOURCES max_element.cpp COMPILE_ONLY)
bcm_test(NAME mpl_min_max SOURCES min_max.cpp COMPILE_ONLY)
bcm_test(NAME mpl_multiset SOURCES multiset.cpp COMPILE_ONLY)
bcm_test(NAME mpl_next SOURCES next.cpp COMPILE_ONLY)
bcm_test(NAME mpl_no_has_xxx SOURCES no_has_xxx.cpp COMPILE_ONLY)
bcm_test(NAME mpl_numeric_ops SOURCES numeric_ops.cpp COMPILE_ONLY)
bcm_test(NAME mpl_pair_view SOURCES pair_view.cpp COMPILE_ONLY)
bcm_test(NAME mpl_partition SOURCES partition.cpp COMPILE_ONLY)
bcm_test(NAME mpl_pop_front SOURCES pop_front.cpp COMPILE_ONLY)
bcm_test(NAME mpl_push_back SOURCES push_back.cpp COMPILE_ONLY)
bcm_test(NAME mpl_push_front SOURCES push_front.cpp COMPILE_ONLY)
bcm_test(NAME mpl_quote SOURCES quote.cpp COMPILE_ONLY)
bcm_test(NAME mpl_range_c SOURCES range_c.cpp COMPILE_ONLY)
bcm_test(NAME mpl_remove SOURCES remove.cpp COMPILE_ONLY)
bcm_test(NAME mpl_remove_if SOURCES remove_if.cpp COMPILE_ONLY)
bcm_test(NAME mpl_replace SOURCES replace.cpp COMPILE_ONLY)
bcm_test(NAME mpl_replace_if SOURCES replace_if.cpp COMPILE_ONLY)
bcm_test(NAME mpl_reverse SOURCES reverse.cpp COMPILE_ONLY)
bcm_test(NAME mpl_same_as SOURCES same_as.cpp COMPILE_ONLY)
bcm_test(NAME mpl_set SOURCES set.cpp COMPILE_ONLY)
bcm_test(NAME mpl_set_c SOURCES set_c.cpp COMPILE_ONLY)
bcm_test(NAME mpl_single_view SOURCES single_view.cpp COMPILE_ONLY)
bcm_test(NAME mpl_size SOURCES size.cpp COMPILE_ONLY)
bcm_test(NAME mpl_size_t SOURCES size_t.cpp)
bcm_test(NAME mpl_sizeof SOURCES sizeof.cpp COMPILE_ONLY)
bcm_test(NAME mpl_sort SOURCES sort.cpp COMPILE_ONLY)
bcm_test(NAME mpl_stable_partition SOURCES stable_partition.cpp COMPILE_ONLY)
bcm_test(NAME mpl_transform SOURCES transform.cpp COMPILE_ONLY)
bcm_test(NAME mpl_transform_view SOURCES transform_view.cpp COMPILE_ONLY)
bcm_test(NAME mpl_unique SOURCES unique.cpp COMPILE_ONLY)
bcm_test(NAME mpl_unpack_args SOURCES unpack_args.cpp COMPILE_ONLY)
bcm_test(NAME mpl_upper_bound SOURCES upper_bound.cpp COMPILE_ONLY)
bcm_test(NAME mpl_vector SOURCES vector.cpp COMPILE_ONLY)
bcm_test(NAME mpl_vector_c SOURCES vector_c.cpp COMPILE_ONLY)
bcm_test(NAME mpl_zip_view SOURCES zip_view.cpp COMPILE_ONLY)
bcm_test(NAME mpl_string SOURCES string.cpp)

