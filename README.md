class N3dal(Abdullah):
   """self-taught developer that love to learn more about Computer-Science and Technologies"""
   
   def __init__(self):
     
      self.name = "Nedal Abdullah"
      self.age = 23
      self.role = "Student"

      self.TOOLS = {
          "ScriptingLanguages" : ("Python", "Bash-Script", "matlab"),
          "ProgrammingLanguages" : ("C", "C++"),
          "MarkupLanguages" : ("Html", "markdown"),
          "OtherLanguages" : ("json", ),
          "Editors" : ("VsCode", "Sublime"),
          "Platform" : ("GNU/LINUX",),
          "OtherTools" : ("GIMP", "Git", "Arduino")
         }

      self.INTERESTS = [
         "Computer Sciences",
         "Electrical & Electronic Engineering",
         "Computer Networks and Networking",
         "Electromagnetic & Antenna Design"
         ]

   def use(self, tool):
      """use one of my tools or use bunch of them."""
      return self.tools[tool]


   def work(self):
      """"""
      while not WORK_DONE:
         # keep work.
         self.use(tool)

      return WORK_DONE


   def __len__(self):
      """Fun Fact"""
      return 181 # cm


   def __repr__(self):
      """"""
      return f"{self.name} an {self.age} y.o self-taught developer and {self.role}"
