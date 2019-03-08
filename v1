=begin 
How Much Wood?

Returns number of 2 x 4's needed based on 
measurements provided.
=end 


def boards(board_length, meas)
  num_boards = 1
  meas_total = 0.0
  
  i = 0
  while i < meas.length
    ele = meas[i]
    meas_total += ele
      
    if meas_total + ele >= board_length 
    # need to check next index of array..
      num_boards += 1
      meas_total *= 0
    end
  
    i += 1
  end
  
  puts "You need " + num_boards.to_s + " board(s)."
  
end
 
puts
boards(96, [
  90.5, 
  90.25, 
  95.625, 
  95.625, 
  87.25, 
  87.25, 
  87.25, 
  23.25, 
  23.25, 
  23.25, 
  23.25, 
  23.25, 
  21.75, 
  21.75, 
  21.75, 
  21.75, 
  21.75, 
])            
puts
