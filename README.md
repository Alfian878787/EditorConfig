# EditorConfig
A very generic EditorConfig file supporting .NET and the web.

```
# http://EditorConfig.org

# This file is the top-most EditorConfig file
root = true

# All Files
[*]
charset = utf-8
end_of_line = crlf
indent_style = space
indent_size = 4
insert_final_newline = false
trim_trailing_whitespace = true

# Solution Files
[*.sln]
indent_style = tab

# XML Project Files
[*.{csproj,vbproj,vcxproj,vcxproj.filters,proj,projitems,shproj}]
indent_size = 2

# Configuration Files
[*.{json,xml,config,yml}]
indent_size = 2

# Markdown Files
[*.md]
trim_trailing_whitespace = false

# Web Files
[*.{html,js,ts,css,scss}]
indent_size = 2
insert_final_newline = true

# Dotnet Code Style Settings (See https://docs.microsoft.com/en-us/visualstudio/ide/editorconfig-code-style-settings-reference)
[*.{cs,vb}]
dotnet_sort_system_directives_first = true:warning
dotnet_style_coalesce_expression = true:warning
dotnet_style_collection_initializer = true:warning
dotnet_style_explicit_tuple_names = true:warning
dotnet_style_null_propagation = true:warning
dotnet_style_object_initializer = true:warning
dotnet_style_predefined_type_for_locals_parameters_members = true:warning
dotnet_style_predefined_type_for_member_access = true:warning
dotnet_style_qualification_for_event = true:warning
dotnet_style_qualification_for_field = true:warning
dotnet_style_qualification_for_method = true:warning
dotnet_style_qualification_for_property = true:warning

# C# Code Style Settings (See https://docs.microsoft.com/en-us/visualstudio/ide/editorconfig-code-style-settings-reference)
[*.cs]
csharp_style_conditional_delegate_call = true:warning
csharp_style_expression_bodied_accessors = true:warning
csharp_style_expression_bodied_constructors = true:warning
csharp_style_expression_bodied_indexers = true:warning
csharp_style_expression_bodied_methods = true:warning
csharp_style_expression_bodied_operators = true:warning
csharp_style_expression_bodied_properties = true:warning
csharp_style_inlined_variable_declaration = true:warning
csharp_style_pattern_matching_over_as_with_null_check = true:warning
csharp_style_pattern_matching_over_is_with_cast_check = true:warning
csharp_style_throw_expression = true:warning
csharp_style_var_elsewhere = true:warning
csharp_style_var_for_built_in_types = true:warning
csharp_style_var_when_type_is_apparent = true:warning
csharp_new_line_before_catch = true:warning
csharp_new_line_before_else = true:warning
csharp_new_line_before_finally = true:warning
csharp_new_line_before_members_in_anonymous_types = true:warning
csharp_new_line_before_members_in_object_initializers = true:warning
csharp_new_line_before_open_brace = all:warning
csharp_new_line_between_query_expression_clauses = true:warning
```
