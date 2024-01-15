# frozen_string_literal: true

markdown("PR number: #{github.pr_json['number']}") 
markdown("PR number: #{github.pr_json['mergeable']}")

rubocop.lint(files: [], force_exclusion: true, inline_comment: true,  report_severity: true, include_cop_names: true)

