module UsersHelper

  def gravstar_for(user)
    gravstar_id = Digest::MD5::hexdigest(user.email.downcase)
    gravstar_url = "https://secure.gravstar.com/avatar/#{gravstar_id}"
    image_tag(gravstar_url, alt: user.name, class: "gravstar")
  end
end
