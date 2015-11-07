---
layout: docs
title: Reserved Variable Names
short_title: Reserved Names
---

The following variables are set internally by **docassemble**.  If you
try to use these reserved names as variable names, you will experience
errors or unexpected results.

* `_internal`: used internally by **docassemble** for various
  purposes, including keeping track of the progress bar, storing the
  answers to multiple-choice questions, and tracking which questions
  have already been answered.
* `current_info`: a dictionary available to the interview code that
  contains some useful information about the interview and the current
  user.  It is pre-set by **docassemble** on every page load.
* `i`: used as an iterator when [generic objects] are defined.
* `role`: used to store the role of the current user for purposes of
  the [roles] system.
* `role_event`: a special variable that is used as part of the [roles]
  system.
* `url_args`: a dictionary available to interview code that contains
  values encoded in the URL with which the interview was initially
  loaded.
* `x`: used as a reference to the underlying object when
  [generic objects] are defined.

If you include the `basic-questions.yml` file from `docassemble.base`,
the list of reserved names expands to the following:

* `Asset`
* `Case`
* `ChildList`
* `Court`
* `DAFileCollection`
* `DAFileList`
* `DAFile`
* `DAList`
* `DATemplate`
* `Document`
* `Expense`
* `FinancialList`
* `Income`
* `Individual`
* `Jurisdiction`
* `LegalFiling`
* `PartyList`
* `PeriodicFinancialList`
* `PeriodicValue`
* `Person`
* `RoleChangeTracker`
* `Value`
* `_internal`
* `advocate`
* `blank_signature`
* `capitalize`
* `case`
* `client`
* `comma_and_list`
* `comma_list`
* `court`
* `currency`
* `current_info`
* `cutoff_date`
* `do_you`
* `does_a_b`
* `force_ask`
* `get_language`
* `her`
* `his`
* `i`
* `indefinite_article`
* `interview_url`
* `jurisdiction`
* `need`
* `nice_number`
* `nodoublequote`
* `noun_plural`
* `ordinal`
* `period_list`
* `pleading`
* `possessify`
* `role`
* `role_event`
* `send_email`
* `set_language`
* `space_to_underscore`
* `spouse`
* `titlecase`
* `today`
* `underscore_to_space`
* `update_info`
* `url_args`
* `url_of`
* `us`
* `user_understands_how_to_use_signature_feature`
* `user_understands_no_attorney_client_relationship`
* `user`
* `verb_past`
* `verb_present`
* `word`
* `words`
* `x`
* `your`

[roles]: {{ site.baseurl }}/docs/roles.html
[generic objects]: {{ site.baseurl }}/docs/modifiers.html