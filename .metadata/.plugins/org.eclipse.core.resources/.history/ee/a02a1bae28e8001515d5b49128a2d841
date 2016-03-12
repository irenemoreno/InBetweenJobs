class Cart
  def initialize(pricing_rules = nil)
    @items = []
    @kr = 3.14
    @me = 42
    @un = 999
  end

  def add item
    @items << item
  end

  def total
    
    kr = @items.count "kr"
      if kr % 2 == 0 then 
          total_kr = (kr.to_i / 2) * @kr
      else
          total_kr = (kr.to_i / 2 + 1) * @kr
      end  

    me = @items.count "me"
      if me >= 3 then @me = 33.33 end
         total_me = me * @me

    un = @items.count "un" 
         total_un = un * @un
   
    price = total_kr + total_me + total_un
    
  end
end

  co = Cart.new
    co.add("me")
    co.add("me")
    co.add("me")
    co.add("me")
    co.add("kr")
    co.add("un")
    co.add("un")
    co.add("un")

  price = co.total
    
puts price