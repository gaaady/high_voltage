rails_versions = %w(
  4.2
  5.0
  5.1
  5.2
)

rails_versions.each do |version|
  appraise "rails_#{version}" do
    gem "rails", "~> #{version}.0"
  end
end

appraise "rails_6.0" do
  gem "rails", "~> 6.0.0.rc1"
end
