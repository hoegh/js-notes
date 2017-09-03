# js-notes
A JavaScript based UI for managing short notes with optional links. Much like the
bookmarks in a browser, just not just links and not tied to a single browser.

The goal is to have something that can run in a browser allowing you to make a note of
a reference to something you might pursue later.

A reference may optionally contain a headline, a text and one or more links (and a
creationdate), and the datamodel will be a list of references. No text-formatting
supported other than explicit linebreaks.

Storage is out of scope, and should be plugable with a load/save semantic for the entire
set of references (as a JSON document) - the goal is to allow it to be hosted externally
or use browser local store, preferable encrypted; but that is another project.

Future expansions might be support for reordering, grouping in topics and internal
references.