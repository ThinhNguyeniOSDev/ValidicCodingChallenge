# ValidicCodingChallenge
This is an iOS take home test for an iOS position at Validic.

# Challenges I ran into:
  - Calcuate percentage of each programming jobs (Not finish). 
  - Write Unit tests.
  - How to model the data of the app.

# Areas of the code I'm most proud of:
  ```
  let endpoint = "https://jobs.github.com/positions.json?description=\(language.lowercased())&location=\(city.lowercased().replacingOccurrences(of: " ", with: "+"))"
  ```
  
# Areas of the code I'm least proud of:
  ```
  lazy var data: [String: [String]] = ["Boston": programmingLanguages,
                                         "San Francisco": programmingLanguages,
                                         "Los Angeles": programmingLanguages,
                                         "Denver": programmingLanguages,
                                         "Boulder": programmingLanguages,
                                         "Chicago": programmingLanguages,
                                         "New York": programmingLanguages,
                                         "Raleigh": programmingLanguages]
  ```
# Tradeoffs I made:
  - Built UI programmatically instead of using Storyboard to speed up development.
  - Used mocking technique to test the networking code to make the test run faster and more isolated. 
  
# Next area of focus to move this beyond MVP:
  - Polish the UI.
  - Write UI Test.
  - Handle error properly.
  - Add data persistence.
