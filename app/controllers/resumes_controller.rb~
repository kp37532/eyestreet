class ResumesController < ApplicationController

def new
end



def upload
  file_field = @params['form']['file'] rescue nil
  # file_field is a StringIO object
  file_field.content_type # 'text/csv'
  file_field.full_original_filename
  ...
end


end
