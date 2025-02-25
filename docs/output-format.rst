.. _output-format:

=============================================================================
Output formats
=============================================================================

This section deals with individual output-format topics.

The command line option ``--output-format=``\ *format* chooses an output format.
Supported *format* are ``u-ctags``, ``e-ctags``, ``etags``, ``xref``, and ``json``.

``u-ctags``, ``e-ctags``
	``u-ctags`` is the default output format extending the Exuberant Ctags
	output format (``e-ctags``).

	``--format=1`` and ``--format=2`` are same as ``--output-format=e-ctags``
	and ``--output-format=u-ctags`` respectively.

	See man page :ref:`tags (5) <tags(5)>` for details. The difference between
	``u-ctags`` and ``e-ctags`` are marked as "EXCEPTION".
	Additional changes in Universal Ctags are described in
	:ref:`changes_tags_file`.

``etags``
	Output format for Emacs etags.

	See the description of ``-e`` option in :ref:`ctags(1) <ctags(1)>`.

``xref``
	A tabular, human-readable cross reference (xref) format.
	``--output-format=xref`` can be abbreviated as ``-x``.

	See section :ref:`output-xref` for details.

``json``
	JSON format.

	See :ref:`ctags-client-tools(7) <ctags-client-tools(7)>`.

*********

.. toctree::
	:maxdepth: 2

	output-tags.rst
	output-xref.rst
