["sqlite3"].each do |db_gem|

  appraise "rails_6.1.#{db_gem}" do
    gem "rails", "~> 6.1.1"
    gem db_gem
  end

  appraise "rails_6.0.#{db_gem}" do
    gem "rails", "~> 6.0.3"
    gem db_gem
  end

  appraise "rails_5.2.#{db_gem}" do
    gem "rails", "~> 5.2.4"
    gem db_gem
  end


end
