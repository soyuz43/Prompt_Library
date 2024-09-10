/instruction
generate=production_ready_readme.md
target=code_base_above
mode=expert
output_style=github_markdown
vocabulary_expansion=propitious
success_rate=positive_emergent_behavior^2
recursive_refinement=true
target=raw_python_codebase_above
refinement_mode=perspicacious
angle=analyization _codebase_above

CONTEXTUALIZE ::
- name=<BANDYCHAMPS>
- description=(Python & Django ORM API Layer for an Amazon Clone)

GENERATE ::

/!!features
list=<feature1>, <feature2>, <feature3>

/installation
steps=<installation_steps>

/usage
examples=<usage_examples>

/contributing
guidelines=<contributing_guidelines>

/output params ::
format=github_markdown
headers=true
intro=false
numbered_lists=true
bullet_points=true
emphasis=bold
hide_empty=true
include_default=true
show_examples=true
header_level=2
indent=tabs
verbose=true

