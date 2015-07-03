# uncrustify
# my objective-c uncrustify.cfg

#
# Uncrustify Configuration File
# File Created With UncrustifyX 0.4.3 (252)
#
 
# Alignment
# ---------
 
## Alignment
 
# Align ObjC declaration params on colon
align_oc_decl_colon                     = true          # boolean (false/true)
 
# Align function prototypes on operator keyword
align_on_operator                       = false         # boolean (false/true)
 
# Align on tabstop
align_on_tabstop                        = false         # boolean (false/true)
 
# Align open brace of single-line functions
align_single_line_brace                 = false         # boolean (false/true)
 
# Align parameters in single-line functions with same name
align_same_func_call_params             = false         # boolean (false/true)
 
# Align single-line functions with function prototypes
align_single_line_func                  = false         # boolean (false/true)
 
# Align variable definitions
align_func_params                       = true          # boolean (false/true)
 
# Align with tabs
align_with_tabs                         = false         # boolean (false/true)
 
# Keep non-indenting tabs
align_keep_tabs                         = false         # boolean (false/true)
 
# Left-align numbers
align_number_left                       = false         # boolean (false/true)
 
## Alignment Span
 
# Alignment span for #define bodies
align_pp_define_span                    = 0             # number
 
# Alignment span for ObjC message colons
align_oc_msg_colon_span                 = 1             # number
 
# Alignment span for ObjC message spec
align_oc_msg_spec_span                  = 0             # number
 
# Alignment span for assignment
align_assign_span                       = 0             # number
 
# Alignment span for equals in enums
align_enum_equ_span                     = 4             # number
 
# Alignment span for function prototypes
align_func_proto_span                   = 0             # number
 
# Alignment span for single-line typedefs
align_typedef_span                      = 0             # number
 
# Alignment span for struct initializer values
align_struct_init_span                  = 0             # number
 
# Alignment span for struct/union
align_var_struct_span                   = 0             # number
 
# Alignment span for trailing comments
align_right_cmt_span                    = 0             # number
 
# Alignment span for variable definitions
align_var_def_span                      = 0             # number
 
## Alignment Style
 
# Alignment style for ampersand in typedefs
align_typedef_amp_style                 = 0             # number
 
# Alignment style for ampersand in variable definitions
align_var_def_amp_style                 = 0             # number
 
# Alignment style for star in typedefs
align_typedef_star_style                = 0             # number
 
# Alignment style for star in variable definitions
align_var_def_star_style                = 0             # number
 
# Alignnment style for typedef'd functions
align_typedef_func                      = 0             # number
 
## Gap
 
# Gap for 'align open brace of single-line functions'
align_single_line_brace_gap             = 0             # number
 
# Gap for aligning struct/union member definitions
align_var_struct_gap                    = 0             # number
 
# Gap for aligning variable definitions
align_var_def_gap                       = 0             # number
 
# Minimum gap between label and value of preprocessor define
align_pp_define_gap                     = 0             # number
 
# Minimum gap between return type and function name
align_func_proto_gap                    = 0             # number
 
# Minimum gap between type and synonym of typedef
align_typedef_gap                       = 0             # number
 
# Minimum gap for trailing comment
align_right_cmt_gap                     = 0             # number
 
## Limits
 
# Align on equals in assignments threshold
align_assign_thresh                     = 0             # number
 
# Align on equals in enums threshold
align_enum_equ_thresh                   = 0             # number
 
# Align struct/union definitions threshold
align_var_struct_thresh                 = 0             # number
 
# Align variable definitions threshold
align_var_def_thresh                    = 0             # number
 
## Other
 
# Align attribute after variable name
align_var_def_attribute                 = false         # boolean (false/true)
 
# Align colon in struct bit fields
align_var_def_colon                     = false         # boolean (false/true)
 
# Align comments after close brace and endif
align_right_cmt_mix                     = false         # boolean (false/true)
 
# Align inline struct/enum/union variable definitions
align_var_def_inline                    = false         # boolean (false/true)
 
# Align left shift operators on new lines
align_left_shift                        = true          # boolean (false/true)
 
# Align macro functions and variables together
align_pp_define_together                = false         # boolean (false/true)
 
# Align macros wrapped with backslash and newline
align_nl_cont                           = false         # boolean (false/true)
 
# Align trailing comments beyond column N
align_right_cmt_at_col                  = 0             # number
 
# Always align with first parameter in ObjC message
align_oc_msg_colon_first                = false         # boolean (false/true)
 
# Mix aligining prototype and variable declarations
align_mix_var_proto                     = false         # boolean (false/true)
 
# Blank Lines
# -----------
 
## Newline After
 
# Newline after Java annotation statement
nl_after_annotation                     = ignore        # string (add/force/ignore/remove)
 
# Newline after multiline comment
nl_after_multiline_comment              = false         # boolean (false/true)
 
## Newline Count After
 
# Newline count after access specifier label
nl_after_access_spec                    = 1             # number
 
# Newline count after close parenthesis of function body in class declaration
nl_after_func_body_class                = 0             # number
 
# Newline count after closing class definition
nl_after_class                          = 0             # number
 
# Newline count after closing struct/enum/union definition
nl_after_struct                         = 0             # number
 
# Newline count after function body
nl_after_func_body                      = 2             # number
 
# Newline count after function prototype
nl_after_func_proto                     = 1             # number
 
# Newline count after function prototype group
nl_after_func_proto_group               = 2             # number
 
# Newline count after single-line function body
nl_after_func_body_one_liner            = 0             # number
 
# Newline count after try-catch-finally
nl_after_try_catch_finally              = 0             # number
 
# Newline count after typedef block
nl_typedef_blk_end                      = 0             # number
 
# Newline count after variable definition block
nl_func_var_def_blk                     = 0             # number
 
# Newline count after variable definition block not at top of function body
nl_var_def_blk_end                      = 0             # number
 
## Newline Count Before
 
# Newline count before C comment
nl_before_c_comment                     = 0             # number
 
# Newline count before C++ comment
nl_before_cpp_comment                   = 0             # number
 
# Newline count before access specifier label
nl_before_access_spec                   = 0             # number
 
# Newline count before multi-line comment
nl_before_block_comment                 = 0             # number
 
# Newline count before typedef block
nl_typedef_blk_start                    = 0             # number
 
# Newline count before variable definition block
nl_var_def_blk_start                    = 0             # number
 
## Newline Count Between
 
# Newline count between function def and function comment
nl_comment_func_def                     = 0             # number
 
# Newline count between get/set/add/remove
nl_between_get_set                      = 0             # number
 
## Newline Count Within
 
# Maximum consecutive newlines within typedef block
nl_typedef_blk_in                       = 0             # number
 
# Maximum consecutive newlines within variable definition block
nl_var_def_blk_in                       = 0             # number
 
## Other
 
# Maximum consecutive newlines
nl_max                                  = 2             # number
 
# Newline count around C# property
nl_around_cs_property                   = 0             # number
 
# Remove blank lines after open brace
eat_blanks_after_open_brace             = true          # boolean (false/true)
 
# Remove blank lines before close brace
eat_blanks_before_close_brace           = true          # boolean (false/true)
 
# Code-Modifying
# --------------
 
## Braces
 
# Braces around fully braced case statement
mod_case_brace                          = ignore        # string (add/force/ignore/remove)
 
# Braces around statments that span N newlines
mod_full_brace_nl                       = 0             # number
 
# Braces on chained if/elseif/else statements
mod_full_brace_if_chain                 = false         # boolean (false/true)
 
# Braces on single-line do statement
mod_full_brace_do                       = ignore        # string (add/force/ignore/remove)
 
# Braces on single-line else statement
mod_full_brace_if                       = ignore        # string (add/force/ignore/remove)
 
# Braces on single-line for statement
mod_full_brace_for                      = ignore        # string (add/force/ignore/remove)
 
# Braces on single-line function definition
mod_full_brace_function                 = ignore        # string (add/force/ignore/remove)
 
# Braces on single-line using statement
mod_full_brace_using                    = ignore        # string (add/force/ignore/remove)
 
# Braces on single-line while statement
mod_full_brace_while                    = ignore        # string (add/force/ignore/remove)
 
## Comments
 
# Add comment after function of size
mod_add_long_function_closebrace_comment = 0            # number
 
# Add comment after ifdef/else statement of size
mod_add_long_ifdef_else_comment         = 0             # number
 
# Add comment after ifdef/endif statement of size
mod_add_long_ifdef_endif_comment        = 0             # number
 
# Add comment after switch statement of size
mod_add_long_switch_closebrace_comment  = 0             # number
 
## Other
 
# Move break in fully-braced case before close brace
mod_move_case_break                     = true          # boolean (false/true)
 
# Remove empty return as last statement in function
mod_remove_empty_return                 = false         # boolean (false/true)
 
## Parentheses
 
# Add parentheses on while and if statements around bool
mod_full_paren_if_bool                  = false         # boolean (false/true)
 
# Remove unnecessary parentheses on return statement
mod_paren_on_return                     = ignore        # string (add/force/ignore/remove)
 
## Semicolons
 
# Change optional semicolons to real semicolons
mod_pawn_semicolon                      = false         # boolean (false/true)
 
# Remove superflous semicolons
mod_remove_extra_semicolon              = true          # boolean (false/true)
 
## Sorting
 
# Sort consecutive import statements
mod_sort_import                         = false         # boolean (false/true)
 
# Sort include statements
mod_sort_include                        = false         # boolean (false/true)
 
# Sort using statements
mod_sort_using                          = false         # boolean (false/true)
 
# Comments
# --------
 
## Comment Files
 
# Class header comment filename
cmt_insert_class_header                 = ""            # string
 
# File footer comment filename
cmt_insert_file_footer                  = ""            # string
 
# File header comment filename
cmt_insert_file_header                  = ""            # string
 
# Function header comment filename
cmt_insert_func_header                  = ""            # string
 
# ObjC message header comment filename
cmt_insert_oc_msg_header                = ""            # string
 
## Empty Lines
 
# Empty first line for multi-line C comments
cmt_c_nl_start                          = false         # boolean (false/true)
 
# Empty first line for multi-line C++ comments
cmt_cpp_nl_start                        = false         # boolean (false/true)
 
# Empty last line for multi-line C comments
cmt_c_nl_end                            = false         # boolean (false/true)
 
# Empty last line for multi-line C++ comments
cmt_cpp_nl_end                          = false         # boolean (false/true)
 
## Other
 
# Change C++ comments to C comments
cmt_cpp_to_c                            = false         # boolean (false/true)
 
# Comment reflow mode
cmt_reflow_mode                         = 0             # number
 
# Comment width
cmt_width                               = 0             # number
 
# Group C comments
cmt_c_group                             = true          # boolean (false/true)
 
# Group C++ comments
cmt_cpp_group                           = true          # boolean (false/true)
 
# Indent multi-line comments
cmt_indent_multi                        = true          # boolean (false/true)
 
# Insert function comment if preprocessor statement
cmt_insert_before_preproc               = false         # boolean (false/true)
 
# Remove leading spaces from multi-line comments
cmt_multi_check_last                    = true          # boolean (false/true)
 
# Stars on multi-line comments
cmt_star_cont                           = true          # boolean (false/true)
 
## Space Count After
 
# Spaces after multi-line comment star
cmt_sp_after_star_cont                  = 0             # number
 
## Space Count Before
 
# Spaces before multi-line comment star
cmt_sp_before_star_cont                 = 0             # number
 
# General
# -------
 
## Other
 
# Input tab size
input_tab_size                          = 4             # number
 
# Interpret >=
tok_split_gte                           = false         # boolean (false/true)
 
# Newline character
newlines                                = auto          # string (auto/cr/crlf/lf)
 
# Output tab size
output_tab_size                         = 2             # number
 
# String escape character
string_escape_char                      = 92            # number
 
# String escape character 2
string_escape_char2                     = 0             # number
 
# Indentation
# -----------
 
## Indentation
 
# Disable indenting class braces
indent_braces_no_class                  = false         # boolean (false/true)
 
# Disable indenting function braces
indent_braces_no_func                   = false         # boolean (false/true)
 
# Disable indenting struct braces
indent_braces_no_struct                 = false         # boolean (false/true)
 
# Double indent size for Indentation options
indent_func_param_double                = false         # boolean (false/true)
 
# Indent ObjC block
indent_oc_block                         = true          # boolean (false/true)
 
# Indent braces
indent_braces                           = false         # boolean (false/true)
 
# Indent class body
indent_class                            = false         # boolean (false/true)
 
# Indent class variable constructors
indent_func_ctor_var_param              = false         # boolean (false/true)
 
# Indent continued function call parameters
indent_func_call_param                  = false         # boolean (false/true)
 
# Indent function call parameters in class declarations
indent_func_class_param                 = false         # boolean (false/true)
 
# Indent function definition parameters
indent_func_def_param                   = false         # boolean (false/true)
 
# Indent function prototype parameters
indent_func_proto_param                 = false         # boolean (false/true)
 
# Indent template parameters
indent_template_param                   = false         # boolean (false/true)
 
## Indentation Size
 
# Indent size based on brace parent
indent_brace_parent                     = false         # boolean (false/true)
 
# Indentation column size
indent_columns                          = 4             # number
 
# Indentation size between case and switch
indent_switch_case                      = 2             # number
 
# Indentation size for ObjC blocks in a message parameter
indent_oc_block_msg                     = 0             # number
 
# Indentation size for ObjC message subsequent parameters
indent_oc_msg_colon                     = 4             # number
 
# Indentation size for multi-line XML strings
indent_xml_string                       = 0             # number
 
# Indentation size for namespace block
indent_namespace_level                  = 0             # number
 
# Indentation size for throw function declaration
indent_func_throw                       = 0             # number
 
# Indentation size of brace after case
indent_case_brace                       = 0             # number
 
# Indentation size of case
indent_case_shift                       = 0             # number
 
# Indentation size of single line comments
indent_sing_line_comments               = 0             # number
 
## Limits
 
# Namespace indentation limit
indent_namespace_limit                  = 0             # number
 
## Other
 
# Align continued statements at equals
indent_align_assign                     = true          # boolean (false/true)
 
# Align strings broken by backslash
indent_align_string                     = false         # boolean (false/true)
 
# Brace indent level
indent_brace                            = 0             # number
 
# Continuation indent
indent_continue                         = -1            # number
 
# Force indentation of function definition to start in column 1
indent_func_def_force_col1              = false         # boolean (false/true)
 
# Indent BOOL inside parentheses
indent_bool_paren                       = false         # boolean (false/true)
 
# Indent access specifier
indent_access_spec                      = 1             # number
 
# Indent after class colon
indent_class_colon                      = false         # boolean (false/true)
 
# Indent code after access specifier
indent_access_spec_body                 = false         # boolean (false/true)
 
# Indent comma inside parentheses
indent_comma_paren                      = false         # boolean (false/true)
 
# Indent comments in first column
indent_col1_comment                     = true          # boolean (false/true)
 
# Indent comments with tabs
indent_cmt_with_tabs                    = false         # boolean (false/true)
 
# Indent content after open square followed by newline
indent_square_nl                        = false         # boolean (false/true)
 
# Indent continued member
indent_member                           = 0             # number
 
# Indent continued variable declarations
indent_var_def_cont                     = false         # boolean (false/true)
 
# Indent else\nif
indent_else_if                          = false         # boolean (false/true)
 
# Indent extern body
indent_extern                           = false         # boolean (false/true)
 
# Indent goto labels
indent_label                            = 1             # number
 
# Indent namespace body
indent_namespace                        = false         # boolean (false/true)
 
# Indent newline content after open parenthesis
indent_paren_nl                         = false         # boolean (false/true)
 
# Indent relative single line comments
indent_relative_single_line_comments    = false         # boolean (false/true)
 
# Indent with tabs
indent_with_tabs                        = 0             # number
 
# Indentation for const qualifier
indent_func_const                       = 0             # number
 
# Indentation for constructor initializer list
indent_ctor_init                        = 0             # number
 
# Indentation of close parenthesis after newline
indent_paren_close                      = 2             # number
 
# Indentation of first BOOL expression
indent_first_bool_expr                  = false         # boolean (false/true)
 
# Preserve SQL indentation
indent_preserve_sql                     = false         # boolean (false/true)
 
# Variable declaration indentation after open brace
indent_var_def_blk                      = 0             # number
 
# Virtual indent from colon for member initializers
indent_ctor_init_leading                = 2             # number
 
# Line-Splitting
# --------------
 
## Other
 
# Split lines as close to code width as possible
ls_code_width                           = false         # boolean (false/true)
 
## Splitting
 
# Code width
code_width                              = 0             # number
 
# Split long for statements at semicolons
ls_for_split_full                       = false         # boolean (false/true)
 
# Split long function prototypes/calls at commas
ls_func_split_full                      = false         # boolean (false/true)
 
# Newlines
# --------
 
## Merging
 
# Change unbraced for statements into one-liner
nl_create_for_one_liner                 = false         # boolean (false/true)
 
# Change unbraced if statements into one-liner
nl_create_if_one_liner                  = false         # boolean (false/true)
 
# Change unbraced while statements into one-liner
nl_create_while_one_liner               = false         # boolean (false/true)
 
## Newline After
 
# Newline after brace close
nl_after_brace_close                    = false         # boolean (false/true)
 
# Newline after brace open
nl_after_brace_open                     = false         # boolean (false/true)
 
# Newline after brace open comment
nl_after_brace_open_cmt                 = false         # boolean (false/true)
 
# Newline after case statement
nl_after_case                           = false         # boolean (false/true)
 
# Newline after comma in constructor arguments
nl_class_init_args                      = ignore        # string (add/force/ignore/remove)
 
# Newline after comma in function declaration
nl_func_decl_args                       = ignore        # string (add/force/ignore/remove)
 
# Newline after comma in function definition
nl_func_def_args                        = ignore        # string (add/force/ignore/remove)
 
# Newline after do
nl_after_do                             = ignore        # string (add/force/ignore/remove)
 
# Newline after for
nl_after_for                            = ignore        # string (add/force/ignore/remove)
 
# Newline after if
nl_after_if                             = ignore        # string (add/force/ignore/remove)
 
# Newline after macro multi-line definition
nl_multi_line_define                    = false         # boolean (false/true)
 
# Newline after open parenthesis in function declaration
nl_func_decl_start                      = remove        # string (add/force/ignore/remove)
 
# Newline after open parenthesis in function declaration if single parameter
nl_func_decl_start_single               = ignore        # string (add/force/ignore/remove)
 
# Newline after open parenthesis in function definition
nl_func_def_start                       = ignore        # string (add/force/ignore/remove)
 
# Newline after open parenthesis in function definition if single parameter
nl_func_def_start_single                = ignore        # string (add/force/ignore/remove)
 
# Newline after return
nl_after_return                         = false         # boolean (false/true)
 
# Newline after semicolon
nl_after_semicolon                      = false         # boolean (false/true)
 
# Newline after square assignment
nl_after_square_assign                  = ignore        # string (add/force/ignore/remove)
 
# Newline after switch
nl_after_switch                         = ignore        # string (add/force/ignore/remove)
 
# Newline after template
nl_template_class                       = add           # string (add/force/ignore/remove)
 
# Newline after virtual brace close
nl_after_vbrace_close                   = false         # boolean (false/true)
 
# Newline after virtual brace open
nl_after_vbrace_open                    = false         # boolean (false/true)
 
# Newline after virtual brace open with empty body
nl_after_vbrace_open_empty              = false         # boolean (false/true)
 
# Newline after while
nl_after_while                          = ignore        # string (add/force/ignore/remove)
 
## Newline Before
 
# Newline before case statement
nl_before_case                          = true          # boolean (false/true)
 
# Newline before close parenthesis in function declaration
nl_func_decl_end                        = remove        # string (add/force/ignore/remove)
 
# Newline before close parenthesis in function declaration if single parameter
nl_func_decl_end_single                 = ignore        # string (add/force/ignore/remove)
 
# Newline before close parenthesis in function definition
nl_func_def_end                         = ignore        # string (add/force/ignore/remove)
 
# Newline before close parenthesis in function definition if single parameter
nl_func_def_end_single                  = ignore        # string (add/force/ignore/remove)
 
# Newline before do
nl_before_do                            = ignore        # string (add/force/ignore/remove)
 
# Newline before for
nl_before_for                           = ignore        # string (add/force/ignore/remove)
 
# Newline before if
nl_before_if                            = ignore        # string (add/force/ignore/remove)
 
# Newline before return
nl_before_return                        = false         # boolean (false/true)
 
# Newline before switch
nl_before_switch                        = ignore        # string (add/force/ignore/remove)
 
# Newline before throw
nl_before_throw                         = ignore        # string (add/force/ignore/remove)
 
# Newline before while
nl_before_while                         = ignore        # string (add/force/ignore/remove)
 
## Newline Between
 
# Newline between C# property and open brace
nl_property_brace                       = ignore        # string (add/force/ignore/remove)
 
# Newline between annotations
nl_between_annotation                   = ignore        # string (add/force/ignore/remove)
 
# Newline between assignment and open brace
nl_assign_brace                         = remove        # string (add/force/ignore/remove)
 
# Newline between brace and brace
nl_brace_brace                          = add           # string (add/force/ignore/remove)
 
# Newline between case colon and open brace
nl_case_colon_brace                     = ignore        # string (add/force/ignore/remove)
 
# Newline between catch and open brace
nl_catch_brace                          = add           # string (add/force/ignore/remove)
 
# Newline between class and open brace
nl_class_brace                          = add           # string (add/force/ignore/remove)
 
# Newline between close brace and catch
nl_brace_catch                          = add           # string (add/force/ignore/remove)
 
# Newline between close brace and else
nl_brace_else                           = remove        # string (add/force/ignore/remove)
 
# Newline between close brace and finally
nl_brace_finally                        = add           # string (add/force/ignore/remove)
 
# Newline between close brace and variable in struct/enum/union
nl_brace_struct_var                     = ignore        # string (add/force/ignore/remove)
 
# Newline between close brace and while
nl_brace_while                          = add           # string (add/force/ignore/remove)
 
# Newline between close parenthesis and open brace in multi line conditional
nl_multi_line_cond                      = false         # boolean (false/true)
 
# Newline between do and open brace
nl_do_brace                             = remove        # string (add/force/ignore/remove)
 
# Newline between else and if
nl_else_if                              = remove        # string (add/force/ignore/remove)
 
# Newline between else and open brace
nl_else_brace                           = remove        # string (add/force/ignore/remove)
 
# Newline between else if and open brace
nl_elseif_brace                         = remove        # string (add/force/ignore/remove)
 
# Newline between enum and open brace
nl_enum_brace                           = remove        # string (add/force/ignore/remove)
 
# Newline between equals and square bracket
nl_assign_square                        = ignore        # string (add/force/ignore/remove)
 
# Newline between finally and open brace
nl_finally_brace                        = force         # string (add/force/ignore/remove)
 
# Newline between for and open brace
nl_for_brace                            = remove        # string (add/force/ignore/remove)
 
# Newline between function call and open brace
nl_fcall_brace                          = add           # string (add/force/ignore/remove)
 
# Newline between function name and open parenthesis
nl_func_paren                           = remove        # string (add/force/ignore/remove)
 
# Newline between function name and open parenthesis in function definition
nl_func_def_paren                       = ignore        # string (add/force/ignore/remove)
 
# Newline between function scope and name in definition
nl_func_scope_name                      = ignore        # string (add/force/ignore/remove)
 
# Newline between function signature and open brace
nl_fdef_brace                           = remove        # string (add/force/ignore/remove)
 
# Newline between get/set and open brace
nl_getset_brace                         = add           # string (add/force/ignore/remove)
 
# Newline between if and open brace
nl_if_brace                             = remove        # string (add/force/ignore/remove)
 
# Newline between namespace and open brace
nl_namespace_brace                      = add           # string (add/force/ignore/remove)
 
# Newline between parentheses in empty function declaration
nl_func_decl_empty                      = ignore        # string (add/force/ignore/remove)
 
# Newline between parentheses in function definition
nl_func_def_empty                       = ignore        # string (add/force/ignore/remove)
 
# Newline between return and expression
nl_return_expr                          = remove        # string (add/force/ignore/remove)
 
# Newline between return type and function name
nl_func_type_name                       = remove        # string (add/force/ignore/remove)
 
# Newline between return type and function name in class
nl_func_type_name_class                 = ignore        # string (add/force/ignore/remove)
 
# Newline between return type and function name in prototype
nl_func_proto_type_name                 = remove        # string (add/force/ignore/remove)
 
# Newline between scope and open brace
nl_scope_brace                          = ignore        # string (add/force/ignore/remove)
 
# Newline between struct and open brace
nl_struct_brace                         = remove        # string (add/force/ignore/remove)
 
# Newline between switch and open brace
nl_switch_brace                         = remove        # string (add/force/ignore/remove)
 
# Newline between try and open brace
nl_try_brace                            = remove        # string (add/force/ignore/remove)
 
# Newline between union and open brace
nl_union_brace                          = add           # string (add/force/ignore/remove)
 
# Newline between unittest and open brace
nl_unittest_brace                       = ignore        # string (add/force/ignore/remove)
 
# Newline between using and open brace
nl_using_brace                          = add           # string (add/force/ignore/remove)
 
# Newline between version and open brace
nl_version_brace                        = ignore        # string (add/force/ignore/remove)
 
# Newline between while and open brace
nl_while_brace                          = remove        # string (add/force/ignore/remove)
 
## Other
 
# Alter newlines in #define macros
nl_define_macro                         = false         # boolean (false/true)
 
# Blank lines after preprocessor if/else
nl_squeeze_ifdef                        = false         # boolean (false/true)
 
# Collapse empty blocks between braces
nl_collapse_empty_body                  = false         # boolean (false/true)
 
# Don't split one-line ObjC messages
nl_oc_msg_leave_one_liner               = false         # boolean (false/true)
 
# Double space before close brace of struct/union/enum
nl_ds_struct_enum_close_brace           = false         # boolean (false/true)
 
# Double space commented entries in struct/enum
nl_ds_struct_enum_cmt                   = false         # boolean (false/true)
 
# Newline around class colon
nl_class_colon                          = ignore        # string (add/force/ignore/remove)
 
# Newline count at end of file
nl_end_of_file_min                      = 1             # number
 
# Newline minimum at start of file
nl_start_of_file_min                    = 0             # number
 
# Newline removal agressiveness
nl_remove_extra_newlines                = 0             # number
 
# Newlines at end of file
nl_end_of_file                          = add           # string (add/force/ignore/remove)
 
# Newlines at start of file
nl_start_of_file                        = remove        # string (add/force/ignore/remove)
 
# Place ObjC message parameters on new lines
nl_oc_msg_args                          = false         # boolean (false/true)
 
## Splitting
 
# Don’t split one-line braced assignments
nl_assign_leave_one_liners              = false         # boolean (false/true)
 
# Don’t split one-line braced statements
nl_class_leave_one_liners               = false         # boolean (false/true)
 
# Don’t split one-line enums
nl_enum_leave_one_liners                = false         # boolean (false/true)
 
# Don’t split one-line function definitions
nl_func_leave_one_liners                = false         # boolean (false/true)
 
# Don’t split one-line get/set functions
nl_getset_leave_one_liners              = false         # boolean (false/true)
 
# Don’t split one-line if/else statements
nl_if_leave_one_liners                  = false         # boolean (false/true)
 
# Other
# -----
 
## Other
 
# Force encoding UTF-8
utf8_force                              = false         # boolean (false/true)
 
# UTF-8 byte order mark
utf8_bom                                = ignore        # string (add/force/ignore/remove)
 
# UTF-8 output if file contains bytes > 128 and < 255
utf8_byte                               = false         # boolean (false/true)
 
# Positioning
# -----------
 
## Constructor
 
# Position of colon after constructor
pos_class_colon                         = ignore        # string (ignore/lead/trail)
 
# Position of comma in constructor
pos_class_comma                         = ignore        # string (ignore/lead/trail)
 
## Wrapped Expressions
 
# Position of arithmetic operators
pos_arith                               = ignore        # string (ignore/lead/trail)
 
# Position of assignment operators
pos_assign                              = ignore        # string (ignore/lead/trail)
 
# Position of boolean operators
pos_bool                                = ignore        # string (ignore/lead/trail)
 
# Position of comma
pos_comma                               = ignore        # string (ignore/lead/trail)
 
# Position of comparison operators
pos_compare                             = ignore        # string (ignore/lead/trail)
 
# Position of ternary operators
pos_conditional                         = lead          # string (ignore/lead/trail)
 
# Preprocessor
# ------------
 
## Indentation
 
# Indent preprocessor define
pp_define_at_level                      = false         # boolean (false/true)
 
# Indent preprocessor if block
pp_indent                               = ignore        # string (add/force/ignore/remove)
 
# Indent preprocessor if/else/endif
pp_if_indent_code                       = false         # boolean (false/true)
 
# Indent preprocessor if/else/endif at level
pp_indent_at_level                      = false         # boolean (false/true)
 
# Indent preprocessor regions
pp_region_indent_code                   = false         # boolean (false/true)
 
## Indentation Size
 
# Preprocessor if/else/endif indent size
pp_indent_if                            = 0             # number
 
# Preprocessor indentation columns
pp_indent_count                         = 1             # number
 
# Preprocessor region indent size
pp_indent_region                        = 0             # number
 
# Preprocessor spaces added
pp_space_count                          = 0             # number
 
## Space After
 
# Space after preprocessor hash in if blocks
pp_space                                = remove        # string (add/force/ignore/remove)
 
## Space Before
 
# Space before preprocessor stringify operator
sp_before_pp_stringify                  = ignore        # string (add/force/ignore/remove)
 
# Spacing
# -------
 
## Other
 
# Balance spaces inside nested parentheses
sp_balance_nested_parens                = false         # boolean (false/true)
 
# Space count before trailing or embedded comment
sp_num_before_tr_emb_cmt                = 0             # number
 
## Space After
 
# Space after C++ comment opening
sp_cmt_cpp_start                        = ignore        # string (add/force/ignore/remove)
 
# Space after ObjC @selector parentheses
sp_after_oc_at_sel_parens               = force         # string (add/force/ignore/remove)
 
# Space after ObjC block caret
sp_after_oc_block_caret                 = remove        # string (add/force/ignore/remove)
 
# Space after ObjC colon
sp_after_oc_colon                       = remove        # string (add/force/ignore/remove)
 
# Space after ObjC dictionary colon
sp_after_oc_dict_colon                  = force         # string (add/force/ignore/remove)
 
# Space after ObjC message colon
sp_after_send_oc_colon                  = remove        # string (add/force/ignore/remove)
 
# Space after ObjC message receiver
sp_after_oc_msg_receiver                = force         # string (add/force/ignore/remove)
 
# Space after ObjC property
sp_after_oc_property                    = force         # string (add/force/ignore/remove)
 
# Space after ObjC return type
sp_after_oc_return_type                 = remove        # string (add/force/ignore/remove)
 
# Space after ObjC scope
sp_after_oc_scope                       = force         # string (add/force/ignore/remove)
 
# Space after ObjC type
sp_after_oc_type                        = remove        # string (add/force/ignore/remove)
 
# Space after address-of operator
sp_addr                                 = remove        # string (add/force/ignore/remove)
 
# Space after angle bracket
sp_after_angle                          = force         # string (add/force/ignore/remove)
 
# Space after assignment in enum
sp_enum_after_assign                    = force         # string (add/force/ignore/remove)
 
# Space after assignment operator
sp_after_assign                         = force         # string (add/force/ignore/remove)
 
# Space after capture specification
sp_cpp_lambda_paren                     = ignore        # string (add/force/ignore/remove)
 
# Space after cast
sp_after_cast                           = remove        # string (add/force/ignore/remove)
 
# Space after class colon
sp_after_class_colon                    = force         # string (add/force/ignore/remove)
 
# Space after comma
sp_after_comma                          = force         # string (add/force/ignore/remove)
 
# Space after condition close parenthesis
sp_after_sparen                         = add           # string (add/force/ignore/remove)
 
# Space after dereference operator
sp_deref                                = remove        # string (add/force/ignore/remove)
 
# Space after double-colon operator
sp_after_dc                             = ignore        # string (add/force/ignore/remove)
 
# Space after final semicolon in empty for statement
sp_after_semi_for_empty                 = ignore        # string (add/force/ignore/remove)
 
# Space after for colon
sp_after_for_colon                      = ignore        # string (add/force/ignore/remove)
 
# Space after invariant close parenthesis
sp_after_invariant_paren                = ignore        # string (add/force/ignore/remove)
 
# Space after invert operator
sp_inv                                  = remove        # string (add/force/ignore/remove)
 
# Space after new
sp_after_new                            = ignore        # string (add/force/ignore/remove)
 
# Space after not operator
sp_not                                  = remove        # string (add/force/ignore/remove)
 
# Space after operator
sp_after_operator                       = ignore        # string (add/force/ignore/remove)
 
# Space after operator and open parenthesis
sp_after_operator_sym                   = ignore        # string (add/force/ignore/remove)
 
# Space after pointer star
sp_after_ptr_star                       = remove        # string (add/force/ignore/remove)
 
# Space after pointer star followed by function
sp_after_ptr_star_func                  = ignore        # string (add/force/ignore/remove)
 
# Space after pointer star if followed by open parenthesis
sp_ptr_star_paren                       = ignore        # string (add/force/ignore/remove)
 
# Space after preprocessor stringify operator
sp_pp_stringify                         = ignore        # string (add/force/ignore/remove)
 
# Space after reference sign
sp_after_byref                          = ignore        # string (add/force/ignore/remove)
 
# Space after reference sign followed by function
sp_after_byref_func                     = ignore        # string (add/force/ignore/remove)
 
# Space after semicolon
sp_after_semi                           = add           # string (add/force/ignore/remove)
 
# Space after semicolon in non-empty for statements
sp_after_semi_for                       = force         # string (add/force/ignore/remove)
 
# Space after sign in assignment
sp_sign                                 = remove        # string (add/force/ignore/remove)
 
# Space after tag keyword
sp_after_tag                            = ignore        # string (add/force/ignore/remove)
 
# Space after throw
sp_after_throw                          = ignore        # string (add/force/ignore/remove)
 
# Space after type
sp_after_type                           = force         # string (add/force/ignore/remove)
 
## Space Around
 
# Space around arithmetic operators
sp_arith                                = add           # string (add/force/ignore/remove)
 
# Space around array initializer colon
sp_d_array_colon                        = ignore        # string (add/force/ignore/remove)
 
# Space around assignment equals in enum
sp_enum_assign                          = ignore        # string (add/force/ignore/remove)
 
# Space around assignment in lambda capture specification
sp_cpp_lambda_assign                    = ignore        # string (add/force/ignore/remove)
 
# Space around assignment operator
sp_assign                               = add           # string (add/force/ignore/remove)
 
# Space around assignment operator in prototype
sp_assign_default                       = add           # string (add/force/ignore/remove)
 
# Space around boolean operators
sp_bool                                 = add           # string (add/force/ignore/remove)
 
# Space around compare operators
sp_compare                              = add           # string (add/force/ignore/remove)
 
# Space around increment/decrement operators
sp_incdec                               = remove        # string (add/force/ignore/remove)
 
# Space around member operators
sp_member                               = remove        # string (add/force/ignore/remove)
 
# Space around preprocessor concatenation operator
sp_pp_concat                            = add           # string (add/force/ignore/remove)
 
# Space around range operator
sp_range                                = ignore        # string (add/force/ignore/remove)
 
# Space around ternary condition colon
sp_cond_colon                           = force         # string (add/force/ignore/remove)
 
# Space around ternary condition question mark
sp_cond_question                        = force         # string (add/force/ignore/remove)
 
## Space Before
 
# Space before ObjC block caret
sp_before_oc_block_caret                = remove        # string (add/force/ignore/remove)
 
# Space before ObjC colon
sp_before_oc_colon                      = remove        # string (add/force/ignore/remove)
 
# Space before ObjC dictionary colon
sp_before_oc_dict_colon                 = force         # string (add/force/ignore/remove)
 
# Space before ObjC message colon
sp_before_send_oc_colon                 = remove        # string (add/force/ignore/remove)
 
# Space before angle brackets
sp_before_angle                         = force         # string (add/force/ignore/remove)
 
# Space before assignment in enum
sp_enum_before_assign                   = ignore        # string (add/force/ignore/remove)
 
# Space before assignment operator
sp_before_assign                        = ignore        # string (add/force/ignore/remove)
 
# Space before backslash-newline at end of line
sp_before_nl_cont                       = add           # string (add/force/ignore/remove)
 
# Space before case colon
sp_before_case_colon                    = remove        # string (add/force/ignore/remove)
 
# Space before class colon
sp_before_class_colon                   = force         # string (add/force/ignore/remove)
 
# Space before comma
sp_before_comma                         = remove        # string (add/force/ignore/remove)
 
# Space before double colon
sp_before_dc                            = ignore        # string (add/force/ignore/remove)
 
# Space before ellipsis
sp_before_ellipsis                      = ignore        # string (add/force/ignore/remove)
 
# Space before empty square brackets
sp_before_squares                       = remove        # string (add/force/ignore/remove)
 
# Space before for colon
sp_before_for_colon                     = ignore        # string (add/force/ignore/remove)
 
# Space before if/for/switch/while open parenthesis
sp_before_sparen                        = force         # string (add/force/ignore/remove)
 
# Space before if/for/while empty statement semicolon
sp_special_semi                         = ignore        # string (add/force/ignore/remove)
 
# Space before open square brackets
sp_before_square                        = remove        # string (add/force/ignore/remove)
 
# Space before pointer star
sp_before_ptr_star                      = force         # string (add/force/ignore/remove)
 
# Space before pointer star followed by function
sp_before_ptr_star_func                 = ignore        # string (add/force/ignore/remove)
 
# Space before reference sign
sp_before_byref                         = ignore        # string (add/force/ignore/remove)
 
# Space before reference sign followed by function
sp_before_byref_func                    = ignore        # string (add/force/ignore/remove)
 
# Space before semicolon
sp_before_semi                          = remove        # string (add/force/ignore/remove)
 
# Space before semicolon in empty for statement
sp_before_semi_for_empty                = ignore        # string (add/force/ignore/remove)
 
# Space before semicolon in for statements
sp_before_semi_for                      = remove        # string (add/force/ignore/remove)
 
# Space before trailing or embedded comment
sp_before_tr_emb_cmt                    = ignore        # string (add/force/ignore/remove)
 
# Space before unnamed pointer star
sp_before_unnamed_ptr_star              = ignore        # string (add/force/ignore/remove)
 
# Space before unnamed reference sign
sp_before_unnamed_byref                 = ignore        # string (add/force/ignore/remove)
 
# Spacing before extern parentheses
sp_extern_paren                         = ignore        # string (add/force/ignore/remove)
 
## Space Between
 
# Space between @selector and open parenthesis
sp_after_oc_at_sel                      = remove        # string (add/force/ignore/remove)
 
# Space between Java annotation and open parenthesis
sp_annotation_paren                     = ignore        # string (add/force/ignore/remove)
 
# Space between __attribute__ and open parenthesis
sp_attribute_paren                      = ignore        # string (add/force/ignore/remove)
 
# Space between angle brackets and open parenthesis
sp_angle_paren                          = ignore        # string (add/force/ignore/remove)
 
# Space between angle brackets and word
sp_angle_word                           = ignore        # string (add/force/ignore/remove)
 
# Space between case and label
sp_case_label                           = ignore        # string (add/force/ignore/remove)
 
# Space between catch and open brace
sp_catch_brace                          = force         # string (add/force/ignore/remove)
 
# Space between catch and open parenthesis
sp_catch_paren                          = force         # string (add/force/ignore/remove)
 
# Space between close brace and else
sp_brace_else                           = force         # string (add/force/ignore/remove)
 
# Space between close brace and typedef name
sp_brace_typedef                        = ignore        # string (add/force/ignore/remove)
 
# Space between close parenthesis and open brace
sp_paren_brace                          = force         # string (add/force/ignore/remove)
 
# Space between close square and open parenthesis in function call
sp_square_fparen                        = ignore        # string (add/force/ignore/remove)
 
# Space between closing brace and catch
sp_brace_catch                          = force         # string (add/force/ignore/remove)
 
# Space between closing brace and finally
sp_brace_finally                        = force         # string (add/force/ignore/remove)
 
# Space between closing parenthesis and open brace
sp_fparen_brace                         = force         # string (add/force/ignore/remove)
 
# Space between constructor and open parenthesis
sp_func_class_paren                     = ignore        # string (add/force/ignore/remove)
 
# Space between defined and open parenthesis
sp_defined_paren                        = ignore        # string (add/force/ignore/remove)
 
# Space between double angle brackets
sp_permit_cpp11_shift                   = false         # boolean (false/true)
 
# Space between double angle brackets
sp_angle_shift                          = add           # string (add/force/ignore/remove)
 
# Space between else and open brace
sp_else_brace                           = force         # string (add/force/ignore/remove)
 
# Space between finally and open brace
sp_finally_brace                        = force         # string (add/force/ignore/remove)
 
# Space between function name and empty parentheses
sp_func_call_paren_empty                = ignore        # string (add/force/ignore/remove)
 
# Space between function name and open parenthesis
sp_func_call_paren                      = remove        # string (add/force/ignore/remove)
 
# Space between function name and open parenthesis in declaration
sp_func_proto_paren                     = remove        # string (add/force/ignore/remove)
 
# Space between function name and open parenthesis in function definition
sp_func_def_paren                       = remove        # string (add/force/ignore/remove)
 
# Space between get/set and open brace
sp_getset_brace                         = ignore        # string (add/force/ignore/remove)
 
# Space between if/for/switch/while close parenthesis and open brace
sp_sparen_brace                         = force         # string (add/force/ignore/remove)
 
# Space between invariant and open parenthesis
sp_invariant_paren                      = ignore        # string (add/force/ignore/remove)
 
# Space between macro and value
sp_macro                                = ignore        # string (add/force/ignore/remove)
 
# Space between macro function close parenthesis and value
sp_macro_func                           = ignore        # string (add/force/ignore/remove)
 
# Space between nested parentheses
sp_paren_paren                          = remove        # string (add/force/ignore/remove)
 
# Space between open parenthesis and comma
sp_paren_comma                          = force         # string (add/force/ignore/remove)
 
# Space between parentheses in function type
sp_after_tparen_close                   = ignore        # string (add/force/ignore/remove)
 
# Space between pointer stars
sp_between_ptr_star                     = remove        # string (add/force/ignore/remove)
 
# Space between preprocessor else and comment
sp_endif_cmt                            = ignore        # string (add/force/ignore/remove)
 
# Space between return and open parenthesis
sp_return_paren                         = ignore        # string (add/force/ignore/remove)
 
# Space between return type and function name
sp_type_func                            = force         # string (add/force/ignore/remove)
 
# Space between scope and open parenthesis
sp_scope_paren                          = ignore        # string (add/force/ignore/remove)
 
# Space between sizeof and open parenthesis
sp_sizeof_paren                         = remove        # string (add/force/ignore/remove)
 
# Space between template and open angle bracket
sp_template_angle                       = ignore        # string (add/force/ignore/remove)
 
# Space between throw and open parenthesis
sp_throw_paren                          = ignore        # string (add/force/ignore/remove)
 
# Space between try and open brace
sp_try_brace                            = force         # string (add/force/ignore/remove)
 
# Space between type and open parenthesis in C++ cast
sp_cpp_cast_paren                       = ignore        # string (add/force/ignore/remove)
 
# Space between user function call and open parenthesis
sp_func_call_user_paren                 = remove        # string (add/force/ignore/remove)
 
# Space between version and open parenthesis
sp_version_paren                        = ignore        # string (add/force/ignore/remove)
 
## Space Inside
 
# Space inside @selector() parens
sp_inside_oc_at_sel_parens              = remove        # string (add/force/ignore/remove)
 
# Space inside angle brackets
sp_inside_angle                         = remove        # string (add/force/ignore/remove)
 
# Space inside braces
sp_inside_braces                        = add           # string (add/force/ignore/remove)
 
# Space inside cast parentheses
sp_inside_paren_cast                    = remove        # string (add/force/ignore/remove)
 
# Space inside empty braces
sp_inside_braces_empty                  = remove        # string (add/force/ignore/remove)
 
# Space inside empty function parentheses
sp_inside_fparens                       = remove        # string (add/force/ignore/remove)
 
# Space inside enum braces
sp_inside_braces_enum                   = ignore        # string (add/force/ignore/remove)
 
# Space inside function parentheses
sp_inside_fparen                        = remove        # string (add/force/ignore/remove)
 
# Space inside if-condition close parenthesis
sp_inside_sparen_close                  = ignore        # string (add/force/ignore/remove)
 
# Space inside if-condition open parenthesis
sp_inside_sparen_open                   = ignore        # string (add/force/ignore/remove)
 
# Space inside if-condition parentheses
sp_inside_sparen                        = remove        # string (add/force/ignore/remove)
 
# Space inside non-empty square brackets
sp_inside_square                        = remove        # string (add/force/ignore/remove)
 
# Space inside parentheses
sp_inside_paren                         = remove        # string (add/force/ignore/remove)
 
# Space inside parentheses in function type
sp_inside_tparen                        = remove        # string (add/force/ignore/remove)
 
# Space inside struct/union braces
sp_inside_braces_struct                 = ignore        # string (add/force/ignore/remove)
