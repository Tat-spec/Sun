# Sundef get_uv_index(level):
    if level < 3:
        return "Low UV Index - Minimal protection required."
    elif level < 6:
        return "Moderate UV Index - Wear sunscreen and protective clothing."
    elif level < 8:
        return "High UV Index - Take extra precautions. Stay in shade near midday."
    elif level < 11:
        return "Very High UV Index - Protection against sun damage is needed."
    else:
        return "Extreme UV Index - Take all precautions. Avoid outdoor activities."

# Example UV index value (normally obtained from a sensor or weather service)
uv_index = 7

# Determine safety recommendations based on UV index level
recommendations = get_uv_index(uv_index)

# Output recommendations
print("UV Index Level:", uv_index)
print("Recommendations:", recommendations)
