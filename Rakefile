require 'html-proofer'

task default: [:test]

task :test do
  HTMLProofer.check_directory("./_site", {
    :typhoeus => {
      :ssl_verifypeer => false,
      :ssl_verifyhost => 0}
  }).run
end