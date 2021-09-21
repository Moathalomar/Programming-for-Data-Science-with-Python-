$git diff
diff --git a/bikeshare.py
b/bikeshare.py
index cd1d149..f4c041f 100644
--- a/bikeshare.py
+++ b/bikeshare.py
@@ -16,6 +16,10 @@ weekdays =
('sunday', 'monday', 'tuesday',
'wednesday', 'thursday', 'friday',
def choice(prompt, choices=('y',
'n')):
"""Return a valid input from the
user given an array of possible
answers.
+
+ Args:
+ (str) prompt - prompt with
input request
+ (tup) choices - tuple with
elements of possible answers
"""
$ git diff
diff --git a/README.md
b/README.md
index 13a6e85..bb56def 100644
--- a/README.md
+++ b/README.md
@@ -5,6 +5,18 @@
### Description
This is a CLI program developed to
allow the user to explore an US
