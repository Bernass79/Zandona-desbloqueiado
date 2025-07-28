local oldreq = request
    hookfunction(request, function(args)
            return {StatusCode=200, Body=game:GetService("HttpService"):JSONEncode({valid=true, message="zandona adora chupar um ovo depilado 🥶🥶"})}
    end)


loadstring(game:HttpGet("https://raw.githubusercontent.com/dadad213/GRANDSCRIPTO/refs/heads/main/script.lua"))()
