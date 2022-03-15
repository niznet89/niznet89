class Person 
  def initialize() 
    @name = 'Tenzin Rose' 
    @occupation = 'Entreprenuer' 
    @interests = ['surfing', 'web3', 'martial arts', 'reading', 'stand up comedy'] 
    @twitter = '@rose_tenzin'
    @linkedin = 'https://www.linkedin.com/in/tenzinrose/'
  end 
  
  def past_projects()
    @previous_employer = { role: 'sales executive', location: ['san francisco, 'new york', 'sydney'], tenure: '7.5 years' } 
    @previous_employers = ['oracle', 'esv']
  end 
  
  def future_projects()
    @future_problems_to_solve = []
    @future_problems_to_solve.each do |problem|
      revenue = 0 
      market_fit = MarketFit.new(timing: problem.timing?, demand: problem.demand?, willing_to_pay: problem.pay?)
      if problem == market_fit
        revenue = '$69,000,000'
      end
  end 
end 
